#
#   $Id: $
#
#   Resume of David M. Syzdek
#   Copyright (C) 2007 David M. Syzdek
#
#   @configure_input@
#
#   Makefile.am - automate compiling on a unix platform
#

# Sub directories
SUBDIRS					=
DIST_SUBDIRS				=


# Global flags
AM_LIBS					=
AM_CFLAGS				=
AM_LDFLAGS				=
AM_CPPFLAGS				=
AM_MAKEINFOFLAGS			= --no-split


# automake targets
bin_PROGRAMS				=
man_MANS				=
info_TEXINFOS				= doc/syzdek-resume.texi
include_HEADERS				=


# macros for doc/syzdek-resume.info
doc_syzdek_resume_TEXINFOS		= doc/syzdek-resume.texi \
					  doc/version-syzdek-resume.texi

# misc lists
TESTS					=
XFAIL_TESTS				=
EXTRA_DIST				= doc/version-syzdek-resume.texi
CLEANFILES				= @PACKAGE_TARNAME@-*.tar.*


# substitution routine
do_subst = sed \
	-e 's,[@]configure_input[@],${@}. Generated from ${@}.in by make.,g' \
	-e 's,[@]SHELL[@],@SHELL@,g' \
	-e 's,[@]PACKAGE_VERSION[@],@PACKAGE_VERSION@,g' \
	-e 's![@]PACKAGE_NAME[@]!@PACKAGE_NAME@!g' \
	-e 's,[@]PACKAGE_TARNAME[@],@PACKAGE_TARNAME@,g' \
	-e 's,[@]PACKAGE_BUGREPORT[@],@PACKAGE_BUGREPORT@,g' \
	-e 's,[@]PACKAGE_COPYRIGHT[@],@PACKAGE_COPYRIGHT@,g' \
	-e 's,[@]RELEASE_MONTH[@],@RELEASE_MONTH@,g'



# local targets
install-exec-local:

install-data-local:

uninstall-local:

distclean-local:
	rm -fR $(srcdir)/autom4te.cache

# end of automake file
