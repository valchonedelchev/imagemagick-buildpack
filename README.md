Build image magick for vulcan:

```
vulcan build -v -s ./ImageMagick-6.8.6-7 -p "/app/vendor/imagemagick" -c "./configure  '--prefix=/app/vendor/imagemagick' '--mandir=/app/vendor/imagemagick/share/man' '--infodir=/app/vendor/imagemagick/share/info' '--with-gs-font-dir=/usr/share/fonts/type1/gsfonts' '--with-magick-plus-plus' '--with-djvu' '--enable-shared' '--without-dps' '--without-fpx' '--with-perl-options=INSTALLDIRS=vendor' '--x-includes=/usr/include/X11' '--x-libraries=/usr/lib/X11' '--enable-delegate-build' 'CFLAGS=-g -O2' 'LDFLAGS=-Wl,-Bsymbolic-functions' 'CPPFLAGS=' 'CXXFLAGS=-g -O2' && make install"
```
