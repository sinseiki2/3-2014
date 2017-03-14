   sudo -s

   apt-get remove libhangul-data

   apt-get install autopoint autoconf autogen libtool gettext gnome-common glib-2.0 ibus-1.0 gtk+-3.0 git

   git clone git://github.com/sinseiki2/libhangul.git libhangul

   cd libhangul

   ./autogen.sh

   ./configure --prefix=/usr

   make

   make install
