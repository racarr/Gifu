## Process this file with automake to produce Makefile.in
## Created by Anjuta

SUBDIRS = data src 

gifudocdir = ${prefix}/doc/gifu
gifudoc_DATA = \
	README\
	COPYING\
	AUTHORS\
	ChangeLog\
	INSTALL\
	NEWS


EXTRA_DIST = $(gifudoc_DATA)


# Remove doc directory on uninstall
uninstall-local:
	-rm -r $(gifudocdir)
