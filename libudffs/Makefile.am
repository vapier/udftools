lib_LTLIBRARIES     = libudffs.la
libudffs_la_SOURCES = crc.c extent.c unicode.c ../include/getopt.h ../include/libudffs.h ../include/ecma_167.h ../include/osta_udf.h ../include/defaults.h ../include/udf_endian.h ../include/bswap.h
libudffs_la_LIBADD = @LTLIBOBJS@
libudffs_la_LDFLAGS = -version-info 1:0:0

AM_CPPFLAGS = -I$(top_srcdir)/include -D_LARGEFILE64_SOURCE
