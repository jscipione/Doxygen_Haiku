#
# This file was generated from Makefile.in on Mon May 23 20:56:57 EDT 2011
#

DOXYGEN   = /Users/jscipione/Projects/doxygen_git_svn
TMAKEPATH = /Users/jscipione/Projects/doxygen_git_svn/tmake/lib/macosx-c++
ENV       = env TMAKEPATH=$(TMAKEPATH)
TMAKE     = /Users/jscipione/Projects/doxygen_git_svn/tmake/bin/tmake
MAKE      = /usr/bin/make
PERL      = /opt/local/bin/perl
RM        = rm -f
CP        = cp
VERSION   = 1.7.4-20110426
INSTALL   = /usr/local
INSTTOOL  = /usr/bin/install
DOXYDOCS  = ..
DOCDIR    = $(INSTALL)/share/doc/packages/doxygen
QTDIR     = 
HAVE_DOT  = /opt/local/bin/dot
MKSPECS   = -spec macx-g++

all clean depend distclean: Makefile.doxyapp 
	$(MAKE) -f Makefile.doxyapp $@

distclean: clean
	$(RM) -rf Makefile doxyapp.pro Makefile.doxyapp

tmake:
	$(ENV) $(PERL) $(TMAKE) doxyapp.pro >Makefile.doxyapp

strip:
	strip doxyapp

Makefile.doxyapp: doxyapp.pro
	$(ENV) $(PERL) $(TMAKE) doxyapp.pro >Makefile.doxyapp

install:
