# $Id$

include ../../config.mk
-include ../../config-local.mk

BFTFILES = *.bft *.xsl
BFTDIR = $(ETCDIR)/bibformat/format_templates

all:
	@echo "Done."

test:
	@echo "Nothing to test."

install:
	$(INSTALL) -m 664 $(BFTFILES) $(BFTDIR)

clean:
	@rm -f *.orig *~
