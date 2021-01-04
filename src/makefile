.PHONY: all
all:
	hugo -d..

.PHONY: clean
clean:
	rm -f ../*.css
	rm -f ../*.html
	rm -f ../*.xml
	rm -fr ../posts
	rm -fr ../tags

.PHONY: server
server:
	hugo server --buildDrafts --buildFuture

