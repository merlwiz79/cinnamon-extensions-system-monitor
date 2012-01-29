ACLOCAL_AMFLAGS = -I m4 ${ACLOCAL_FLAGS}

SUBDIRS = src po

bin_SCRIPTS = cinnamon-system-monitor-config

desktopdir       = $(datadir)/applications
desktop_DATA     = $(desktop_in_files:.desktop.in=.desktop)
desktop_in_files = cinnamon-system-monitor-config.desktop.in

@INTLTOOL_DESKTOP_RULE@

EXTRA_DIST = $(bin_SCRIPTS) \
	cinnamon-system-monitor-config.desktop		\
	$(desktop_in_files)		
