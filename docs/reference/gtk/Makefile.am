DOC_MODULE = gtk4

DOC_MAIN_SGML_FILE = gtk4-docs.xml

SCAN_OPTIONS = --deprecated-guards="GTK_ENABLE_BROKEN|GTK_DISABLE_DEPRECATED"

DOC_SOURCE_DIR = $(top_srcdir)/gtk $(top_builddir)/gtk

HFILE_GLOB=$(top_srcdir)/gtk/*.h
CFILE_GLOB=$(top_srcdir)/gtk/*.c

# Header files to ignore when scanning
IGNORE_HFILES = \
	inspector			\
	a11y				\
	gtkaccelgroupprivate.h		\
	gtkaccelmapprivate.h		\
	gtkadjustmentprivate.h		\
	gtkallocatedbitmaskprivate.h	\
	gtkappchooserprivate.h		\
	gtkapplicationaccelsprivate.h	\
	gtkapplicationprivate.h		\
	gtkbindingsprivate.h		\
	gtkbitmaskprivate.h		\
	gtkboxgadgetprivate.h	        \
	gtkboxprivate.h		        \
	gtkbuilderprivate.h		\
	gtkbuiltiniconprivate.h		\
	gtkbuttonprivate.h		\
	gtkcellareaboxcontextprivate.h	\
	gtkcheckbuttonprivate.h		\
	gtkclipboardprivate.h		\
	gtkcolorchooserprivate.h	\
	gtkcoloreditorprivate.h		\
	gtkcolorplaneprivate.h		\
	gtkcolorscaleprivate.h		\
	gtkcolorswatchprivate.h		\
	gtkcolorutils.h			\
	gtkcomboboxprivate.h		\
	gtkcomposetable.h		\
	gtkcontainerprivate.h		\
	gtkcssanimatedstyleprivate.h	\
	gtkcssanimationprivate.h	\
	gtkcssarrayvalueprivate.h	\
	gtkcssbgsizevalueprivate.h	\
	gtkcssbordervalueprivate.h	\
	gtkcsscalcvalueprivate.h	\
	gtkcsscolorvalueprivate.h	\
	gtkcsscornervalueprivate.h	\
	gtkcsscustomgadgetprivate.h	\
	gtkcsscustompropertyprivate.h	\
	gtkcssdimensionvalueprivate.h	\
	gtkcsseasevalueprivate.h	\
	gtkcssenginevalueprivate.h	\
	gtkcssenumvalueprivate.h	\
	gtkcssgadgetprivate.h		\
	gtkcssiconthemevalueprivate.h	\
	gtkcssimagebuiltinprivate.h	\
	gtkcssimagecrossfadeprivate.h	\
	gtkcssimagefallbackprivate.h	\
	gtkcssimagegradientprivate.h	\
	gtkcssimageiconthemeprivate.h	\
	gtkcssimagelinearprivate.h	\
	gtkcssimageradialprivate.h	\
	gtkcssimageprivate.h		\
	gtkcssimagerecolorprivate.h	\
	gtkcssimagescaledprivate.h	\
	gtkcssimagesurfaceprivate.h	\
	gtkcssimageurlprivate.h		\
	gtkcssimagevalueprivate.h	\
	gtkcssimagewin32private.h	\
	gtkcssinheritvalueprivate.h	\
	gtkcssinitialvalueprivate.h	\
	gtkcsskeyframesprivate.h	\
	gtkcsslookupprivate.h		\
	gtkcssmatcherprivate.h		\
	gtkcssnodeprivate.h		\
	gtkcssnodestylecacheprivate.h	\
	gtkcssnodedeclarationprivate.h	\
	gtkcssnumbervalueprivate.h	\
	gtkcsspalettevalueprivate.h	\
	gtkcsspathnodeprivate.h		\
	gtkcssparserprivate.h		\
	gtkcsspositionvalueprivate.h	\
	gtkcssproviderprivate.h		\
	gtkcssrepeatvalueprivate.h	\
	gtkcssrgbavalueprivate.h	\
	gtkcsssectionprivate.h		\
	gtkcssselectorprivate.h		\
	gtkcssshadowsvalueprivate.h	\
	gtkcssshadowvalueprivate.h	\
	gtkcssshorthandpropertyprivate.h\
	gtkcssstaticstyleprivate.h	\
	gtkcssstringvalueprivate.h	\
	gtkcssstylechangeprivate.h	\
	gtkcssstylefuncsprivate.h	\
	gtkcssstyleprivate.h		\
	gtkcssstylepropertyprivate.h	\
	gtkcsstransformvalueprivate.h	\
	gtkcsstransientnodeprivate.h	\
	gtkcsstransitionprivate.h	\
	gtkcsstypedvalueprivate.h	\
	gtkcsstypesprivate.h		\
	gtkcssunsetvalueprivate.h	\
	gtkcssvalueprivate.h		\
	gtkcsswidgetnodeprivate.h	\
	gtkcsswin32sizevalueprivate.h	\
	gtkdebugupdatesprivate.h	\
	gtkdialogprivate.h		\
	gtkdndprivate.h			\
	gtkentryprivate.h		\
	gtkeventcontrollerprivate.h	\
	gtkfilechoosernativeprivate.h	\
	gtkfilechooserprivate.h		\
	gtkfilechooserwidgetprivate.h	\
	gtkfontchooserprivate.h		\
	gtkgesturedragprivate.h		\
	gtkgesturelongpressprivate.h	\
	gtkgesturemultipressprivate.h	\
	gtkgesturepanprivate.h		\
	gtkgestureprivate.h		\
	gtkgesturerotateprivate.h	\
	gtkgesturesingleprivate.h	\
	gtkgestureswipeprivate.h	\
	gtkgesturezoomprivate.h		\
	gtkheaderbarprivate.h		\
	gtkhslaprivate.h		\
	gtkiconprivate.h		\
	gtkiconhelperprivate.h		\
	gtkiconthemeprivate.h		\
	gtkiconviewprivate.h		\
	gtkimagedefinitionprivate.h	\
	gtkimageprivate.h		\
	gtkimcontextsimpleprivate.h	\
	gtkimmoduleprivate.h		\
	gtklabelprivate.h		\
	gtklockbuttonprivate.h		\
	gtkmagnifierprivate.h		\
	gtkmenubuttonprivate.h		\
	gtkmenuitemprivate.h		\
	gtkmenuprivate.h		\
	gtkmenushellprivate.h		\
	gtkmodulesprivate.h		\
	gtkmountoperationprivate.h	\
	gtkorientableprivate.h		\
	gtkpixelcacheprivate.h		\
	gtkplacessidebarprivate.h	\
	gtkplacesviewprivate.h		\
	gtkplacesviewrowprivate.h	\
	gtkpopoverprivate.h		\
	gtkprinter-private.h		\
	gtkprintoperation-private.h	\
	gtkprivate.h		        \
	gtkprogresstrackerprivate.h     \
	gtkrangeprivate.h		\
	gtkrecentchooserprivate.h	\
	gtkrenderbackgroundprivate.h	\
	gtkrenderborderprivate.h	\
	gtkrendericonprivate.h		\
	gtkroundedboxprivate.h		\
	gtkscaleprivate.h		\
	gtksearchengine.h		\
	gtksearchenginemodel.h		\
	gtksearchenginequartz.h		\
	gtksearchenginesimple.h		\
	gtksearchenginetracker.h	\
	gtksearchentryprivate.h		\
	gtkselectionprivate.h		\
	gtksettingsprivate.h		\
	gtkshortcutsshortcutprivate.h	\
	gtkshortcutswindowprivate.h	\
	gtksidebarrowprivate.h		\
	gtksizegroup-private.h		\
	gtksizerequestcacheprivate.h	\
	gtksnapshotprivate.h		\
	gtkstyleanimationprivate.h	\
	gtkstylecascadeprivate.h	\
	gtkstylecontextprivate.h	\
	gtkstylepropertyprivate.h	\
	gtkstyleproviderprivate.h	\
	gtktextattributes.h		\
	gtktextattributesprivate.h	\
	gtktextchildprivate.h		\
	gtktexthandleprivate.h		\
	gtktextiterprivate.h		\
	gtktextmarkprivate.h		\
	gtktexttagprivate.h		\
	gtktextviewprivate.h		\
	gtktogglebuttonprivate.h	\
	gtktoolbarprivate.h		\
	gtktoolpaletteprivate.h		\
	gtktooltipprivate.h		\
	gtktooltipwindowprivate.h	\
	gtkutilsprivate.h		\
	gtktreeprivate.h		\
	gtkwidgetprivate.h		\
	gtkwin32themeprivate.h		\
	gtkwindowprivate.h		\
	fnmatch.h			\
	gtkactionmuxer.h		\
	gtkactionobserver.h		\
	gtkactionobservable.h		\
	gtk9slice.h			\
	gtkanimationdescription.h	\
	gtkbitmaskprivateimpl.h		\
	gtkbookmarksmanager.h		\
	gtkdbusgenerated.c		\
	gtkdbusgenerated.h		\
	gtkdebug.h			\
	gtkactionhelper.h		\
	gtkdndcursors.h			\
	gtkfilechooserdefault.h		\
	gtkfilechooserembed.h		\
	gtkfilechooserentry.h		\
	gtkfilechoosersettings.h	\
	gtkfilechooserutils.h		\
	gtkfilesystem.h			\
	gtkfilesystemmodel.h		\
	gtkfilesystemunix.h		\
	gtkfilesystemwin32.h		\
	gtkfontchooserutils.h		\
	gtkiconcache.h			\
        gtkiconcachevalidator.h         \
	gtkiconthemeparser.h		\
	gtkintl.h			\
	gtkkeyhash.h			\
	gtkkineticscrolling.h		\
	gtkmarshal.h			\
	gtkmnemonichash.h		\
	gtkmenutracker.h		\
	gtkmenutrackeritem.h		\
	gtkmenusectionbox.h		\
	gtkmodelmenu.h			\
	gtkmodelmenuitem.h		\
	gtkmodifierstyle.h		\
	gtkpathbar.h			\
	gtkprintbackend.h		\
	gtkprinteroption.h		\
	gtkprinteroptionset.h		\
	gtkprinteroptionwidget.h	\
	gtkprinter-private.h		\
	gtkprintoperation-portal.h	\
	gtkprint-win32.h		\
	gtkprintutils.h			\
	gtkprivate.h			\
	gtkprivatetypebuiltins.h	\
	gtkquery.h			\
	gtkrbtree.h			\
	gtkrecentchooserdefault.h	\
	gtkrecentchooserutils.h		\
	gtksearchengine.h		\
	gtksearchenginetracker.h	\
	gtksearchenginesimple.h		\
	gtksearchenginequartz.h		\
	gtksequence.h			\
	gtktextbtree.h			\
	gtktextbufferserialize.h	\
	gtktextdisplay.h		\
	gtktextlayout.h			\
	gtktextsegment.h		\
	gtktexttypes.h			\
	gtktextutil.h			\
	gtktimeline.h			\
	gtkthemes.h			\
	gtktrashmonitor.h		\
	gtktrayicon.h			\
	gtktreedatalist.h		\
	gtktreemenu.h			\
	gtktypebuiltins.h		\
	gtkwidgetpathprivate.h		\
	gtkwindow-decorate.h		\
	gtkwin32drawprivate.h		\
	gtkwin32themeprivate.h		\
	xdgmime				\
	xembed.h			\
	$()

AM_CPPFLAGS = \
	-I$(top_srcdir) 	\
	-I$(top_builddir) 	\
	-I$(top_builddir)/gdk	\
	-DGTK_ENABLE_BROKEN	\
	-Wno-deprecated-declarations \
	$(GTK_DEBUG_FLAGS)	\
	$(GTK_DEP_CFLAGS)

CPPFLAGS += \
	-UGTK_DISABLE_SINGLE_INCLUDES

GTKDOC_LIBS = \
	$(top_builddir)/gtk/libgtk-4.la	\
	$(GTK_DEP_LIBS)


# Extra options to supply to gtkdoc-mkdb
MKDB_OPTIONS = --output-format=xml --name-space=gtk

# Extra SGML files that are included by $(DOC_MAIN_SGML_FILE)
content_files = \
	broadway.xml				\
	building.sgml				\
	compiling.sgml				\
	css-overview.xml			\
	css-properties.xml			\
	drawing-model.xml			\
	getting_started.xml			\
	glossary.xml				\
	gtk4-broadwayd.xml			\
	gtk4-demo-application.xml		\
	gtk4-demo.xml				\
	gtk4-icon-browser.xml			\
	gtk4-widget-factory.xml			\
	gtk4-builder-tool.xml			\
	gtk4-encode-symbolic-svg.xml		\
	gtk4-launch.xml				\
	gtk4-query-immodules.xml		\
	gtk4-query-settings.xml			\
	gtk4-update-icon-cache.xml		\
	input-handling.xml			\
	migrating-2to4.xml			\
	migrating-3to4.xml			\
	mir.xml					\
	osx.sgml				\
	overview.xml 				\
	question_index.sgml			\
	resources.sgml				\
	running.sgml				\
	text_widget.sgml			\
	tree_widget.sgml			\
	version.xml				\
	visual_index.xml			\
	wayland.xml				\
	windows.sgml				\
	x11.sgml				\
	$()

expand_content_files = \
	compiling.sgml				\
	drawing-model.xml			\
	getting_started.xml			\
	glossary.xml				\
	input-handling.xml			\
	migrating-2to4.xml			\
	migrating-3to4.xml			\
	question_index.sgml			\
	text_widget.sgml			\
	tree_widget.sgml			\
	$()

# Images to copy into HTML directory
HTML_IMAGES = \
	$(srcdir)/images/aboutdialog.png				\
	$(srcdir)/images/accel-label.png				\
	$(srcdir)/images/action-bar.png					\
	$(srcdir)/images/appchooserbutton.png				\
	$(srcdir)/images/appchooserdialog.png				\
	$(srcdir)/images/assistant.png					\
	$(srcdir)/images/box-packing.png				\
	$(srcdir)/images/box-expand.png					\
	$(srcdir)/images/button.png					\
	$(srcdir)/images/check-button.png				\
	$(srcdir)/images/color-button.png				\
	$(srcdir)/images/colorchooser.png				\
	$(srcdir)/images/combo-box.png					\
	$(srcdir)/images/combo-box-entry.png				\
	$(srcdir)/images/combo-box-text.png				\
	$(srcdir)/images/entry.png					\
	$(srcdir)/images/figure-hierarchical-drawing.png		\
	$(srcdir)/images/figure-windowed-label.png			\
	$(srcdir)/images/file-button.png				\
	$(srcdir)/images/filechooser.png				\
	$(srcdir)/images/font-button.png				\
	$(srcdir)/images/fontchooser.png				\
	$(srcdir)/images/frame.png					\
	$(srcdir)/images/glarea.png					\
	$(srcdir)/images/headerbar.png					\
	$(srcdir)/images/icon-view.png					\
	$(srcdir)/images/image.png					\
	$(srcdir)/images/info-bar.png					\
	$(srcdir)/images/label.png					\
	$(srcdir)/images/levelbar.png					\
	$(srcdir)/images/link-button.png				\
	$(srcdir)/images/list-and-tree.png				\
	$(srcdir)/images/lock-button.png				\
	$(srcdir)/images/lockbutton.png	        			\
	$(srcdir)/images/lockbutton-locked.png				\
	$(srcdir)/images/lockbutton-unlocked.png			\
	$(srcdir)/images/lockbutton-sorry.png				\
	$(srcdir)/images/menubar.png					\
	$(srcdir)/images/menu-button.png				\
	$(srcdir)/images/messagedialog.png				\
	$(srcdir)/images/multiline-text.png				\
	$(srcdir)/images/notebook.png					\
	$(srcdir)/images/panes.png					\
	$(srcdir)/images/pagesetupdialog.png				\
	$(srcdir)/images/placessidebar.png				\
	$(srcdir)/images/popup-anchors.png				\
	$(srcdir)/images/popup-flip.png					\
	$(srcdir)/images/popup-slide.png				\
	$(srcdir)/images/printdialog.png				\
	$(srcdir)/images/progressbar.png				\
	$(srcdir)/images/radio-group.png				\
	$(srcdir)/images/recentchooserdialog.png			\
	$(srcdir)/images/scales.png					\
	$(srcdir)/images/scrollbar.png					\
	$(srcdir)/images/scrolledwindow.png				\
	$(srcdir)/images/search-bar.png					\
	$(srcdir)/images/search-entry.png				\
	$(srcdir)/images/separator.png					\
	$(srcdir)/images/sidebar.png					\
	$(srcdir)/images/spinbutton.png					\
	$(srcdir)/images/spinner.png					\
	$(srcdir)/images/stack.png					\
	$(srcdir)/images/stackswitcher.png				\
	$(srcdir)/images/statusbar.png					\
	$(srcdir)/images/toggle-button.png				\
	$(srcdir)/images/toolbar.png					\
	$(srcdir)/images/toolpalette.png				\
	$(srcdir)/images/tree-view-coordinates.png			\
	$(srcdir)/images/volumebutton.png				\
	$(srcdir)/images/window.png					\
	$(srcdir)/images/layout-btlr.png				\
	$(srcdir)/images/layout-btrl.png				\
	$(srcdir)/images/layout-lrbt.png				\
	$(srcdir)/images/layout-lrtb.png				\
	$(srcdir)/images/layout-rlbt.png				\
	$(srcdir)/images/layout-rltb.png				\
	$(srcdir)/images/layout-tblr.png				\
	$(srcdir)/images/layout-tbrl.png				\
	$(srcdir)/images/widget-hvalign.png				\
	$(srcdir)/images/window-default.png				\
	$(srcdir)/images/hello-world.png				\
	$(srcdir)/images/grid-packing.png				\
	$(srcdir)/images/drawing.png					\
	$(srcdir)/images/switch.png					\
	$(srcdir)/images/linear.png					\
	$(srcdir)/images/ease.png					\
	$(srcdir)/images/ease-in-out.png				\
	$(srcdir)/images/ease-in.png					\
	$(srcdir)/images/ease-out.png					\
	$(srcdir)/images/gradient1.png					\
	$(srcdir)/images/gradient2.png					\
	$(srcdir)/images/gradient3.png					\
	$(srcdir)/images/gradient4.png					\
	$(srcdir)/images/border1.png					\
	$(srcdir)/images/border2.png					\
	$(srcdir)/images/border3.png					\
	$(srcdir)/images/slices.png					\
	$(srcdir)/images/checks.png					\
	$(srcdir)/images/options.png					\
	$(srcdir)/images/arrows.png					\
	$(srcdir)/images/expanders.png					\
	$(srcdir)/images/background.png					\
	$(srcdir)/images/frames.png					\
	$(srcdir)/images/frame-gap.png					\
	$(srcdir)/images/sliders.png					\
	$(srcdir)/images/focus.png					\
	$(srcdir)/images/handles.png					\
	$(srcdir)/images/extensions.png					\
	$(srcdir)/images/bloatpad-osx.png				\
	$(srcdir)/images/bloatpad-gnome.png				\
	$(srcdir)/images/bloatpad-xfce.png				\
	$(srcdir)/images/down-center.png				\
	$(srcdir)/images/down-end.png					\
	$(srcdir)/images/down-start.png					\
	$(srcdir)/images/left-center.png				\
	$(srcdir)/images/left-end.png					\
	$(srcdir)/images/left-start.png					\
	$(srcdir)/images/right-center.png				\
	$(srcdir)/images/right-end.png					\
	$(srcdir)/images/right-start.png				\
	$(srcdir)/images/up-center.png					\
	$(srcdir)/images/up-end.png					\
	$(srcdir)/images/up-start.png					\
	$(srcdir)/images/list-box.png					\
	$(srcdir)/images/getting-started-app1.png			\
	$(srcdir)/images/getting-started-app2.png			\
	$(srcdir)/images/getting-started-app3.png			\
	$(srcdir)/images/getting-started-app4.png			\
	$(srcdir)/images/getting-started-app6.png			\
	$(srcdir)/images/getting-started-app7.png			\
	$(srcdir)/images/getting-started-app8.png			\
	$(srcdir)/images/getting-started-app9.png			\
	$(srcdir)/images/getting-started-app10.png			\
	$(srcdir)/images/exampleapp.png					\
	$(srcdir)/images/flow-box.png					\
	$(srcdir)/images/inspector.png					\
	$(srcdir)/images/gedit-shortcuts.png				\
	$(srcdir)/images/clocks-shortcuts.png				\
	$(srcdir)/images/builder-shortcuts.png

if ENABLE_DOC_CROSS_REFERENCES
# Extra options to supply to gtkdoc-fixref
FIXXREF_OPTIONS=--extra-dir=../gdk/html \
	--extra-dir=$(GLIB_PREFIX)/share/gtk-doc/html/gobject \
	--extra-dir=$(GLIB_PREFIX)/share/gtk-doc/html/glib \
	--extra-dir=$(GLIB_PREFIX)/share/gtk-doc/html/gio \
	--extra-dir=$(ATK_PREFIX)/share/gtk-doc/html/atk \
	--extra-dir=$(PANGO_PREFIX)/share/gtk-doc/html/pango \
	--extra-dir=$(CAIRO_PREFIX)/share/gtk-doc/html/cairo
endif

include $(top_srcdir)/gtk-doc.make

# Other files to distribute
EXTRA_DIST += version.xml.in gtk4.types.in

########################################################################

man_MANS = 				\
	gtk4-broadwayd.1		\
	gtk4-builder-tool.1 		\
	gtk4-demo.1			\
	gtk4-demo-application.1		\
	gtk4-encode-symbolic-svg.1	\
	gtk4-icon-browser.1		\
	gtk4-launch.1			\
	gtk4-query-immodules.1		\
	gtk4-query-settings.1		\
	gtk4-update-icon-cache.1	\
	gtk4-widget-factory.1

if ENABLE_MAN

XSLTPROC_FLAGS = \
        --nonet \
        --stringparam man.output.quietly 1 \
        --stringparam funcsynopsis.style ansi \
        --stringparam man.th.extra1.suppress 1 \
        --stringparam man.authors.section.enabled 0 \
        --stringparam man.copyright.section.enabled 0

.xml.1:
	$(AM_V_GEN) $(XSLTPROC) $(XSLTPROC_FLAGS) http://docbook.sourceforge.net/release/xsl/current/manpages/docbook.xsl $<

dist-local-check-mans-enabled:
	if grep "Man generation disabled" $(man_MANS) >/dev/null; then $(RM) $(man_MANS); fi

else

$(man_MANS):
	echo Man generation disabled.  Creating dummy $@.  Configure with --enable-man to enable it.
	echo Man generation disabled.  Remove this file, configure with --enable-man, and rebuild > $@

dist-local-check-mans-enabled:
	echo "*** --enable-man must be used in order to make dist"
	false

endif

MAINTAINERCLEANFILES = $(man_MANS) $(BUILT_SOURCES)

EXTRA_DIST += $(man_MANS)

if ENABLE_GTK_DOC
TESTS_ENVIRONMENT = cd $(srcdir) && \
  DOC_MODULE=$(DOC_MODULE) DOC_MAIN_SGML_FILE=$(DOC_MAIN_SGML_FILE) \
  SRCDIR=$(abs_srcdir) BUILDDIR=$(abs_builddir)
#TESTS = $(GTKDOC_CHECK)
endif

dist-hook-local: dist-local-check-mans-enabled all-local

gtk-docs-clean: clean
	cd $(srcdir) && rm -rf xml html

-include $(top_srcdir)/git.mk
