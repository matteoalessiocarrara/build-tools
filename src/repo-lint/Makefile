# Abbellisce un repo


# WARNING Deve essere definita sulla riga di comando di make
REPO_ROOT = ""
DOC_DIR = $(REPO_ROOT)/doc
CHANGELOG_FILE = $(DOC_DIR)/CHANGELOG.md
AUTHORS_FILE = $(DOC_DIR)/AUTHORS.md


# Procedura per aggiungere operazioni
# 1: aggiungere l'operazione
# 2: aggiungerla ad "all"
# 3: modificare "clean"


all: doc


doc: authors changelog


authors:
	mkdir --parents $(DOC_DIR)
	git gen-authors > $(AUTHORS_FILE)


changelog:
	mkdir --parents $(DOC_DIR)
	git gen-changelog > $(CHANGELOG_FILE)


clean:
	rm -f $(AUTHORS_FILE)
	rm -f $(CHANGELOG_FILE)
