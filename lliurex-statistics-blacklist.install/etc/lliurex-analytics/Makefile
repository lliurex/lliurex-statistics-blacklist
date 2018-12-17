.PHONY: all
edit:
	@editor blacklist.txt
all:	blacklist.txt
	@sort blacklist.txt |uniq > b
	@mv b blacklist.txt
	@echo `cat blacklist.txt|wc -l` words sorted