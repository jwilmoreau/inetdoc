ifndef $(MAIN_DIR)
MAIN_DIR = $(HOME)/inetdoc
endif

# Liste des répertoires à traiter à partir de ce niveau
SUBDIRS = \
	files

# Type(s) de traitement
PROCESS = subdirs qonly symlink xml2xhtml xml2pdf

SYMLINKS = \
        $(MAIN_DIR)/common/author.xml \
        $(MAIN_DIR)/common/legal.xml \
        $(MAIN_DIR)/common/inetdoc.urls.xml \
        $(MAIN_DIR)/common/rfc.urls.xml

XML_FILES = \
	interco.netfilter.q.xml \
	inetdoc.urls.xml \
	rfc.urls.xml

all: $(PROCESS)

include $(MAIN_DIR)/common/Makefile.Rules
