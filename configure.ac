#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.71])
AC_INIT([asm6809],[2.13])
AM_INIT_AUTOMAKE([foreign])
AC_CONFIG_SRCDIR([src/asm6809.c])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CC
gl_EARLY
AC_PROG_YACC
AC_PROG_LEX([noyywrap])

# Checks for libraries.

# Checks for header files.
gl_INIT
AC_FUNC_ALLOCA
AC_CHECK_HEADERS([inttypes.h libintl.h malloc.h stddef.h stdint.h stdlib.h string.h unistd.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_INT16_T
AC_TYPE_INT32_T
AC_TYPE_INT64_T
AC_TYPE_INT8_T
AC_TYPE_SIZE_T
AC_TYPE_UINT16_T
AC_TYPE_UINT32_T
AC_TYPE_UINT8_T

# Checks for library functions.
AC_FUNC_ERROR_AT_LINE
AC_CHECK_FUNCS([malloc realloc strtod memset strerror strndup strtol])

AC_CONFIG_FILES([Makefile gnulib/Makefile dt101/Makefile src/Makefile man/Makefile tests/Makefile])
AC_OUTPUT
