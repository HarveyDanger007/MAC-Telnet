if INSTALL_CONFIG
dist_sysconf_DATA = mactelnetd.users

install-exec-hook:
	chmod 600 $(DESTDIR)$(sysconfdir)/mactelnetd.users
		chown root $(DESTDIR)$(sysconfdir)/mactelnetd.users
else
dist_sysconf_DATA =
endif