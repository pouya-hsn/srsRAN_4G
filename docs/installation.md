git clone https://github.com/pouya-hsn/srsRAN_4G.git

cd srsRAN_4G

mkdir build

cd build

cmake ../

make -j$(nproc)
