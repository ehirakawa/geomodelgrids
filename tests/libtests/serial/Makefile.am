subpackage = serial
include $(top_srcdir)/subpackage.am
include $(top_srcdir)/check.am

TESTS = test_serial

check_PROGRAMS = test_serial

test_serial_SOURCES = \
	TestModelInfo.cc \
	TestBlock.cc \
	TestTopography.cc \
	TestModel.cc \
	test_driver.cc

noinst_HEADERS =

test_serial_LDFLAGS = $(AM_LDFLAGS)
test_serial_LDADD = \
	-lcppunit -ldl \
	$(top_builddir)/libsrc/geomodelgrids/libgeomodelgrids.la \
	-lhdf5


# End of file
