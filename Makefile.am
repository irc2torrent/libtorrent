SUBDIRS = src test

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libtorrent.pc

EXTRA_DIST= \
	scripts/checks.m4 \
	scripts/common.m4 \
	scripts/attributes.m4 \
	scripts/ssl.m4 \
	doc/main.xml \
	doc/http.xml \
	doc/torrent.xml

# The macro directory is declared by AC_CONFIG_MACRO_DIRS in configure.ac.
# Repeating it here as ACLOCAL_AMFLAGS is redundant, and libtool 2.5.4 makes
# the duplicate a fatal libtoolize error.
