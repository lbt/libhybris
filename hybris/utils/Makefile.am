bin_PROGRAMS = \
	getprop \
	setprop

getprop_SOURCES = getprop.c
getprop_CFLAGS = \
	-I$(top_srcdir)/include -I$(top_srcdir)/include/android
getprop_LDADD = \
	$(top_builddir)/properties/libandroid-properties.la

setprop_SOURCES = setprop.c
setprop_CFLAGS = \
	-I$(top_srcdir)/include
setprop_LDADD = \
	$(top_builddir)/properties/libandroid-properties.la
