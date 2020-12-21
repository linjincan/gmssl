# gmssl
wget http://www.openssl.org/source/openssl-1.0.2f.tar.gz
tar -xzf openssl-1.0.2f.tar.gz
cd openssl-1.0.2f
mkdir /usr/local/openssl
./config --prefix=/usr/local/openssl --openssldir=/usr/local/openssl -Wl,-rpath,/usr/local/openssl/lib shared
make
make install


/usr/local/lib64
