# Questo è un makefile predefinito da posizionare nella directory src di un repo
# Per funzionare necessita di:
# * https://github.com/matteoalessiocarrara/build-tools


DOC_DIR = ../doc
CHANGELOG_FILE = $(DOC_DIR)/CHANGELOG.md
AUTHORS_FILE = $(DOC_DIR)/AUTHORS.md


all: authors changelog


authors:
	mkdir --parents $(DOC_DIR)
	git gen-authors > $(AUTHORS_FILE)

changelog:
	mkdir --parents $(DOC_DIR)
	git gen-changelog > $(CHANGELOG_FILE)