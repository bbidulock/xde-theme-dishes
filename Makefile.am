
AUTOMAKE_OPTIONS = nostdinc

dist_xdetheme_DATA = \
	theme/theme.ini

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
	mkdir -p $(DESTDIR)$(waimeastylesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(waimeastylesdir)/$(style)
	mkdir -p $(DESTDIR)$(fluxboxstylesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(fluxboxstylesdir)/$(style)
	mkdir -p $(DESTDIR)$(blackboxstylesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(blackboxstylesdir)/$(style)
	mkdir -p $(DESTDIR)$(icewmthemesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(icewmthemesdir)/$(style)
	mkdir -p $(DESTDIR)$(jwmthemesdir)
	$(LN_S) ../styles/$(basestyle) $(DESTDIR)$(jwmthemesdir)/$(style)
	mkdir -p $(DESTDIR)$(ctwmstylesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(ctwmstylesdir)/$(style)
	mkdir -p $(DESTDIR)$(vtwmstylesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(vtwmstylesdir)/$(style)
	mkdir -p $(DESTDIR)$(twmstylesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(twmstylesdir)/$(style)
	mkdir -p $(DESTDIR)$(pekwmthemesdir)
	$(LN_S) $(basestyle) $(DESTDIR)$(pekwmthemesdir)/$(style)
	mkdir -p $(DESTDIR)$(themedir)
	$(LN_S) ../$(basestyle)/openbox-3 $(DESTDIR)$(themedir)/openbox-3
	mkdir -p $(DESTDIR)$(themedir)
	$(LN_S) ../$(basestyle)/gtk-2.0 $(DESTDIR)$(themedir)/gtk-2.0
	mkdir -p $(DESTDIR)$(wmakerthemedir)
	mkdir -p $(DESTDIR)$(fluxboxbgdir)
	mkdir -p $(DESTDIR)$(blackboxbgdir)
	mkdir -p $(DESTDIR)$(wmakerbgdir)
	mkdir -p $(DESTDIR)$(xdeimagedir)
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

