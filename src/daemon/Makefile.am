@CODE_COVERAGE_RULES@

INCLUDES = -I$(top_srcdir)/src -I$(top_srcdir)/include

if WITH_DAEMON

sbin_PROGRAMS = cgrulesengd
cgrulesengd_SOURCES = cgrulesengd.c cgrulesengd.h ../tools/tools-common.h ../tools/tools-common.c
cgrulesengd_LIBS = $(CODE_COVERAGE_LIBS)
cgrulesengd_CFLAGS = $(CODE_COVERAGE_CFLAGS)
cgrulesengd_LDADD = $(top_builddir)/src/.libs/libcgroup.la -lrt
cgrulesengd_LDFLAGS = -L$(top_builddir)/src/.libs

endif
