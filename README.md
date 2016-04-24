3-2014
======

Korean 3-moachigi-2014 (Sebeolsik Moachigi 2015)


How to apply.<br><br>
   sudo apt-get install nabi<br>
   wget http://libhangul.googlecode.com/files/libhangul-0.1.0.tar.gz<br>
   tar xvf libhangul-0.1.0.tar.gz<br>
   sudo apt-get install git<br>
   git clone git://github.com/Sinseiki2/3-2014.git 314<br>
   cp 314/po/ko.po libhangul-0.1.0/po/ko.po<br>
   cp 314/hangul/hangulkeyboard.h libhangul-0.1.0/hangul/hangulkeyboard.h<br>
   cp 314/hangul/hangulinputcontext.c libhangul-0.1.0/hangul/hangulinputcontext.c<br>
   cp 314/hangul/hangul.h libhangul-0.1.0/hangul/hangul.h<br>
   cd libhangul-0.1.0<br>
   ./configure --prefix=/usr<br>
   make<br>
   sudo make install

