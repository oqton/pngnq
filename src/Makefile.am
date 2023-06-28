AM_CFLAGS = -Wall --pedantic -std=gnu99 @PNG_CFLAGS@

bin_PROGRAMS = pngnq pngcomp
pngnq_SOURCES = pngnq.c neuquant32.c rwpng.c  neuquant32.h rwpng.h errors.h
pngnq_LDADD  = @PNG_LIBS@
pngcomp_SOURCES = pngcomp.c rwpng.c colorspace.c  colorspace.h
pngcomp_LDADD  = @PNG_LIBS@
