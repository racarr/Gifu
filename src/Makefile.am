## Process this file with automake to produce Makefile.in
## Created by Anjuta

## The main script
SUBDIRS = sgf library engine review actors

bin_SCRIPTS = gifu

## Directory where .class files will be installed
gifudir = $(pythondir)/gifu

gifu_PYTHON = \
	__init__.py  \
	util.py \
	dirs.py 

dirs.py: dirs.py.in
	sed -e "s|%pkgdatadir%|$(pkgdatadir)|" $< > $@