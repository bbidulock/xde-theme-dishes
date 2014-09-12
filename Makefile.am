
AUTOMAKE_OPTIONS = nostdinc

dist_xdetheme_DATA = \
	theme/theme.ini \
	theme/themerc

dist_wmakertheme_DATA = \
	theme/style

dist_xdeimage_DATA = \
	images/hoghorns_millet3.jpg \
	images/hoghorn.jpg \
	images/oregon-peak.jpg \
	images/two_hoghorns2.jpg \
	images/hoghorns_milletC.jpg \
	images/horn_dishes_centered.jpg \
	images/relay_dishes.jpg

EXTRA_DIST = \
	images/backyard.jpg \
	images/blackheath.jpg \
	images/bradsully.jpg \
	images/brocoli.jpg \
	images/cakepans.jpg \
	images/dishes_frost.jpg \
	images/dishes_urals.jpg \
	images/dish_mist.jpg \
	images/dish_sunset.jpg \
	images/dish_wires.jpg \
	images/dome_dishes.jpg \
	images/high_dishes.jpg \
	images/hoghorn.jpg \
	images/hoghorns_millet1.jpg \
	images/hoghorns_millet2.jpg \
	images/hoghorns_millet3.jpg \
	images/hoghorns_millet4.jpg \
	images/hoghorns_millet5.jpg \
	images/hoghorns_millet6.jpg \
	images/hoghorns_millet7.jpg \
	images/hoghorns_millet8.jpg \
	images/hoghorns_millet9.jpg \
	images/hoghorns_milletA.jpg \
	images/hoghorns_milletB.jpg \
	images/hoghorns_milletC.jpg \
	images/hoghorns_milletD.jpg \
	images/hoghorn_valley.jpg \
	images/horn_dishes_centered.jpg \
	images/horn_dishes.jpg \
	images/lightfoot.jpg \
	images/oregon-peak.jpg \
	images/rare_centered.jpg \
	images/rare.jpg \
	images/relay_dishes.jpg \
	images/ryerson.jpg \
	images/storm_dishes2.jpg \
	images/storm_dishes.jpg \
	images/teleport.jpg \
	images/telesat.jpg \
	images/tower_all.jpg \
	images/tower_dishes5.jpg \
	images/tower_glow.jpg \
	images/tower.jpg \
	images/tower_mast.jpg \
	images/twin_towers.jpg \
	images/two_hoghorns2.jpg \
	images/two_hoghorns.jpg

install-data-hook:
	$(MKDIR_P) $(DESTDIR)$(adwmstylesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(adwmstylesdir)/$(style)
	$(MKDIR_P) $(DESTDIR)$(waimeastylesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(waimeastylesdir)/$(style)
	$(MKDIR_P) $(DESTDIR)$(fluxboxstylesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(fluxboxstylesdir)/$(style)
	$(MKDIR_P) $(DESTDIR)$(blackboxstylesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(blackboxstylesdir)/$(style)
	$(MKDIR_P) $(DESTDIR)$(icewmthemesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(icewmthemesdir)/$(style)
	$(MKDIR_P) $(DESTDIR)$(jwmthemesdir)
	$(LN_S) ../styles/$(basestyle) $(DESTDIR)$(jwmthemesdir)/$(style)
	$(MKDIR_P) $(DESTDIR)$(ctwmstylesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(ctwmstylesdir)/$(style)
	$(MKDIR_P) $(DESTDIR)$(vtwmstylesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(vtwmstylesdir)/$(style)
	$(MKDIR_P) $(DESTDIR)$(twmstylesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(twmstylesdir)/$(style)
	$(MKDIR_P) $(DESTDIR)$(pekwmthemesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(pekwmthemesdir)/$(style)
	$(MKDIR_P) $(DESTDIR)$(themedir)
	$(LN_S) ../$(basestyle)/openbox-3 $(DESTDIR)$(themedir)/openbox-3
	$(MKDIR_P) $(DESTDIR)$(themedir)
	$(LN_S) ../$(basestyle)/gtk-2.0 $(DESTDIR)$(themedir)/gtk-2.0
	$(MKDIR_P) $(DESTDIR)$(wmakerthemedir)
	$(MKDIR_P) $(DESTDIR)$(fluxboxbgdir)
	$(MKDIR_P) $(DESTDIR)$(blackboxbgdir)
	$(MKDIR_P) $(DESTDIR)$(wmakerbgdir)
	$(MKDIR_P) $(DESTDIR)$(xdeimagedir)
	for p in $(dist_xdeimage_DATA) ; do \
		f=$$(basename $$p .jpg) ; \
		install -m644 $(top_srcdir)/images/$$f.jpg $(DESTDIR)$(xdeimagedir)/$$f.jpg ; \
		$(LN_S) ../../../images/$(stylesubdir)/$$f.jpg $(DESTDIR)$(wmakerthemedir)/$$f.jpg ; \
		$(LN_S) ../../images/$(stylesubdir)/$$f.jpg $(DESTDIR)$(fluxboxbgdir)/$$f.jpg ; \
		$(LN_S) ../../images/$(stylesubdir)/$$f.jpg $(DESTDIR)$(blackboxbgdir)/$$f.jpg ; \
		$(LN_S) ../../images/$(stylesubdir)/$$f.jpg $(DESTDIR)$(wmakerbgdir)/$$f.jpg ; \
	done
	for f in $(baseprefix)back $(baseprefix)icon $(baseprefix)tbar $(baseprefix)tile ; do \
		$(LN_S) ../../../WindowMaker/Pixmaps/$$f.xpm $(DESTDIR)$(wmakerthemedir)/$$f.xpm ; \
	done

