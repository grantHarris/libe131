AM_CFLAGS = -Wall -O3 -std=gnu11 -pedantic
ACLOCAL_AMFLAGS = -I m4

dist_doc_DATA = LICENSE README.md

lib_LTLIBRARIES = libe131.la
libe131_la_SOURCES = src/e131.c
libe131_la_LDFLAGS = -export-symbols-regex '^[eE]131_[^_]' -version-info 1:3:1
include_HEADERS = src/e131.h
