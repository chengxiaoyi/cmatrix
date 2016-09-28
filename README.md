yum install gcc make autoconf automake ncurses-devel

wget http://www.asty.org/cmatrix/dist/cmatrix-1.2a.tar.gz

tar xzvf cmatrix-1.2a.tar.gz

cd cmatrix-1.2a

aclocal

autoconf

automake -a



./configure

make

sudo make install



cmatrix -h

Linux Install cMatrix from RPM,DEB,XZ, or Source
