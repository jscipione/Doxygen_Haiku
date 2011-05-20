#
# This file was generated from Makefile.in on Thu May 19 16:42:16 EDT 2011
#

DOXYGEN   = /Users/jscipione/Projects/doxygen_git_svn
TMAKEPATH = /Users/jscipione/Projects/doxygen_git_svn/tmake/lib/macosx-c++
ENV       = env TMAKEPATH=$(TMAKEPATH)
TMAKE     = /Users/jscipione/Projects/doxygen_git_svn/tmake/bin/tmake
MAKE      = /usr/bin/make
PERL      = /usr/bin/perl
RM        = rm -f
CP        = cp
VERSION   = 1.7.4-20110426
INSTALL   = /usr/local
INSTTOOL  = /usr/bin/install
DOXYDOCS  = ..
DOCDIR    = $(INSTALL)/share/doc/packages/doxygen
QTDIR     = 
MKSPECS   = -spec macx-g++
all clean depend: Makefile.xmlparse 
	$(MAKE) -f Makefile.xmlparse $@

distclean: clean
	$(RM) -rf Makefile.xmlparse xmlparse.pro Makefile obj

tmake:
	$(ENV) $(PERL) $(TMAKE) xmlparse.pro >Makefile.xmlparse

Makefile.xmlparse: xmlparse.pro
	$(ENV) $(PERL) $(TMAKE) xmlparse.pro >Makefile.xmlparse

install:
