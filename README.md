ddwrt-wifi-hang-workaround
==========================

Contains a shell script that will detect and restart ath0 on ddwrt routers that are experiencing WiFi hang issues

More details at: http://www.dd-wrt.com/phpBB2/viewtopic.php?p=647529

**Prerequisites**

1. Enable system logging via syslogd: http://www.dd-wrt.com/wiki/index.php/Logging_with_DD-WRT
2. Setup startup scripts: http://www.dd-wrt.com/wiki/index.php/Startup_Scripts
3. Setup jffs: http://www.dd-wrt.com/wiki/index.php/Jffs
4. Setup terminal access

It's easiest to take the script and paste it into your terminal after typing the following:

1. cat - > /jffs/etc/config/checkwifi.startup
2. chmod 700 /jffs/etc/config/checkwifi.startup

This should just give you the flavor of what's involved: see the URLs above for more information
