sudo apt update
sudo apt install g++ make cmake m4 yasm nasm 
cd QD-master
./configure
make 
sudo make install
cd ..
make
./gpulucas
