3-2014
======

Korean 3-moachigi-2014


How to apply.
   sudo apt-get install nabi
   wget http://libhangul.googlecode.com/files/libhangul-0.1.0.tar.gz 
   tar xvf libhangul-0.1.0.tar.gz
   sudo apt-get install git
   git clone git://github.com/Sinseiki/3-2014.git 314
   cp 314/po/ko.po libhangul-0.1.0/po/ko.po
   cp 314/hangul/hangulkeyboard.h libhangul-0.1.0/hangul/hangulkeyboard.h
   cp 314/hangul/hangulinputcontext.c libhangul-0.1.0/hangul/hangulinputcontext.c
   cd libhangul-0.1.0
   ./configure --prefix=/usr
   make
   sudo make install

