libdir=@PAM_MODS_DIR@
lib_LTLIBRARIES=pam_mysql.la
noinst_FILES=pam_mysql.la pam_mysql.a
pam_mysql_la_SOURCES=pam_mysql.c
pam_mysql_la_LDFLAGS=-module -avoid-version
pam_mysql_la_LIBADD=-lpam
AM_CPPFLAGS=@AM_CPPFLAGS@ -I/usr/include/security/
EXTRA_DIST=COPYING NEWS README CREDITS ChangeLog INSTALL pam_mysql.spec.in install-sh missing mkinstalldirs pkg.m4 pam_mysql.spec
