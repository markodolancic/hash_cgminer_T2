# hash_cgminer_T2

source ~/ti-processor-sdk-linux-am335x-evm-04.01.00.06/linux-devkit/environment-setup
[linux-devkit]:~/bitcion/git_work/cgminer_T2/cgminer> 
make distclean

./configure --enable-bitmine_A1 --without-curses --host=arm-linux-gnueabi --build=x86_64-pc-linux-gnu PKG_CONFIG_LIBDIR=/home/dong/bitcion/cpuminer/CPUMiner_git/usr/curl/lib/pkgconfig

make
