EXTRA_DIST = \
	Lioshi \
	COPYING \
	AUTHORS \
	README.md

themedir = $(datadir)/themes

install-data-hook:
	$(MKDIR_P) $(DESTDIR)/usr/share/themes
	cp -Rv Lioshi $(DESTDIR)/usr/share/themes/.

uninstall-hook:
	test -e $(DESTDIR)/usr/share/themes/Lioshi && rm -rfv $(DESTDIR)/usr/share/themes/Lioshi