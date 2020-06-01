############################################################ IDENT(1)
#
# $Title: Makefile for installing viotop $
# $Copyright: 2020 Devin Teske. All rights reserved. $
# $FrauBSD: vimcat/GNUmakefile 2020-05-31 22:00:37 -0700 freebsdfrau $
#
############################################################ CONFIGURATION

DESTDIR=	
BINDIR=		$(DESTDIR)/usr/bin

############################################################ PATHS

CP_F=		cp -f
MKDIR_P=	mkdir -p
RM_F=		rm -f

############################################################ OBJECTS

PROG=		vimcat

############################################################ TARGETS

all:
	@printf "Options:\n"
	@printf "\tmake install\tInstall $(PROG)\n"
	@printf "\tmake uninstall\tUninstall $(PROG)\n"

install:
	$(MKDIR_P) $(BINDIR)
	$(CP_F) $(PROG) $(BINDIR)/
	$(CP_F) $(PROG)n $(BINDIR)/

uninstall:
	$(RM_F) $(BINDIR)/$(PROG) $(BINDIR)/$(PROG)n

################################################################################
# END
################################################################################
