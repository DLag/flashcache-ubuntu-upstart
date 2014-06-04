flashcache-ubuntu-upstart
=========================

###Facebook Flashcache Ubuntu Upstart script

Edit /etc/flashcache/caches

	ssd	cachedev	sysctl_dev_name	mount_point

Rename /etc/flashcache/cachedev.start with name of cache device

Then

	chmod +x /etc/flashcache/*.start

Reboot