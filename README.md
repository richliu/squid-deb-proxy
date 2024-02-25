
Squid-deb-proxy for Gentoo 

Due to Gentoo doesn't have squid-deb-proxy package, 
just make one for personal use purpose. 

Original version is debian version, and add ubuntu mirror
For gentoo it needs to emerge squid first. 
https://tracker.debian.org/pkg/squid-deb-proxy

The initial script is OpenRC version, I don't have systemd version gentoo.

[Install] 

Just copy all files in src to / 
run following command to start it.
$ /etc/init.d/squid-deb-proxy start 
