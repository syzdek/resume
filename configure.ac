#
#   $Id: $
#
#   Resume of David M. Syzdek
#   Copyright (C) 2007 David M. Syzdek
#
#   configure.ac - automate compiling on a unix platform
#

# +-=-=-=-=-=-=-=-=-+
# |                 |
# |  Autoconf Init  |
# |                 |
# +-=-=-=-=-=-=-=-=-+

AC_PREREQ(2.61)

AC_COPYRIGHT([Copyright (c) 2007 David M. Syzdek <david@syzdek.net>])
AC_INIT([Resume of David M. Syzdek],[src],[syzdek@bindlebinaries.net],[syzdek-resume])

# Library Version Info:
#    Current    -- the current version number of this API
#    Revision   -- the revision of the implementation of the API version
#    Age        -- How many seqential past API versions is supported by
#                  this implementation
# Format => Current:Revision:Age
#AC_SUBST(LIB_VERSION_INFO, 0:0:0)
#AC_SUBST(LIB_RELEASE_INFO, 0) # used by Win32 DLLs

AC_CONFIG_AUX_DIR([build-aux])
AC_CONFIG_SRCDIR([.])
#AC_CONFIG_LIBOBJ_DIR(compat)
AC_CONFIG_HEADER([config.h])

# determines host type
#AC_CANONICAL_BUILD
#AC_CANONICAL_HOST
#AC_CANONICAL_TARGET

# Compilers
#AC_PROG_CC
#AM_PROG_CC_C_O
#AC_PROG_INSTALL

# checks for Unix Variants
#AC_AIX
#AC_GNU_SOURCE
#AC_MINIX
#AC_C_BIGENDIAN

# binary locations
#AC_PROG_INSTALL
#AC_PATH_PROG([SHELL],   sh bash,        [AC_MSG_ERROR([missing "sh"])], [$PATH])
#AC_CHECK_TOOLS(AR,      ar gar,         [AC_MSG_ERROR([missing binutil "ar"])])
#AC_CHECK_TOOLS(LD,      ld gld,         [AC_MSG_ERROR([missing binutil "ld"])])
#AC_CHECK_TOOLS(NM,      nm gnm,         [AC_MSG_ERROR([missing binutil "nm"])])
#AC_CHECK_TOOLS(RANLIB,  ranlib granlib, [AC_MSG_ERROR([missing binutil "ranlib"])])
#AC_CHECK_TOOLS(STRIP,   strip gstrip,   [AC_MSG_ERROR([missing binutil "strip"])])

# GNU Libtool Support
#AC_LIBTOOL_DLOPEN
#AC_DISABLE_FAST_INSTALL
#AC_LIBTOOL_WIN32_DLL
#AC_PROG_LIBTOOL

# configures for automake
AM_INIT_AUTOMAKE(gnu std-options subdir-objects)

# output files
AC_CONFIG_FILES([Makefile])
AC_OUTPUT

# Show local config
AC_MSG_NOTICE([ ])
AC_MSG_NOTICE([   David Syzdek's Resume])
AC_MSG_NOTICE([ ])
AC_MSG_NOTICE([   Available Formats:])
AC_MSG_NOTICE([      make html])
AC_MSG_NOTICE([      make info])
AC_MSG_NOTICE([      make pdf])
AC_MSG_NOTICE([ ])
AC_MSG_NOTICE([   Make All Formats:])
AC_MSG_NOTICE([      make resume])
AC_MSG_NOTICE([ ])

# end of autoconf script
