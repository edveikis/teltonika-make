bin_PROGRAMS = penguin
penguin_SOURCES = penguin.cpp
bin_SCRIPTS = bin/penguin
AUTOMAKE_OPTIONS = foreign subdir-objects

all-am: penguin
	touch bin/penguin.sh
	
penguin: bin/penguin.sh
	@sed "s|__datadir__|@datadir@|" $< >bin/$@

clean-local:
	@rm config.status configure config.log
	@rm Makefile 
	@rm -r autom4te.cache/
	@rm aclocal.m4 
	@rm compile install-sh missing Makefile.in