plugin_LTLIBRARIES = irissquare.la
irissquare_la_LDFLAGS = -avoid-version -module -shared 
irissquare_la_LIBADD = 
irissquare_la_SOURCES = irissquare.C 
AM_CXXFLAGS = $(LARGEFILE_CFLAGS)

INCLUDES = -I$(top_srcdir)/guicast -I$(top_srcdir)/cinelerra -I$(top_srcdir)/quicktime
LIBTOOL = $(SHELL) $(top_builddir)/libtool $(LTCXX_FLAGS)

noinst_HEADERS = irissquare.h picon_png.h 
EXTRA_DIST = picon.png
