noinst_LTLIBRARIES = compat.la

compat_la_SOURCES = strndup.c asprintf.c
compat_la_CPPFLAGS = -I$(top_srcdir) $(PTHREADS_CFLAGS) $(RSRT_CFLAGS)
compat_la_LDFLAGS = -module -avoid-version
compat_la_LIBADD = $(IMUDP_LIBS)
