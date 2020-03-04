# redsea-ubuntu-binary


From https://github.com/windytan/redsea   A lightweight RDS to JSON decoder


Test:

wget http://mirrors.kernel.org/ubuntu/pool/universe/l/liquid-dsp/libliquid1d_1.3.1-1_amd64.deb

dpkg -x libliquid1d_1.3.1-1_amd64.deb .

cp  usr/lib/x86_64-linux-gnu/libliquid.* /usr/lib/x86_64-linux-gnu/

apt-get install libfftw3-3 -y

wget https://github.com/op07n/redsea/raw/master/mpx.wav

wget https://github.com/op07n/redsea-ubuntu-binary/releases/download/refs%2Fheads%2Fmaster/redsea

chmod +x redsea

./redsea -f mpx.wav
