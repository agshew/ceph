libosdc_la_SOURCES = \
	osdc/Objecter.cc \
	osdc/ObjectCacher.cc \
	osdc/Filer.cc \
	osdc/Striper.cc \
	osdc/Journaler.cc

if WITH_BLKIN
libosdc_la_CPPFLAGS = -DWITH_BLKIN $(AM_CPPFLAGS)
libosdc_la_CXXFLAGS = $(BLKIN_CFLAGS) $(AM_CXXFLAGS)
libosdc_la_LIBADD = $(BLKIN_LIBS)
endif

noinst_LTLIBRARIES += libosdc.la

noinst_HEADERS += \
	osdc/Filer.h \
	osdc/Journaler.h \
	osdc/ObjectCacher.h \
	osdc/Objecter.h \
	osdc/Striper.h \
	osdc/WritebackHandler.h

