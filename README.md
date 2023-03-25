These are my notes on installing Nextcloud on Raspberry Pi and getting a green checkmark on the Administration Overview page.

My last installation is in '00. Nextcloud 25.0.4 on Raspberry Pi 4 running Bullseye, mysql, apache and Let's Encrypt certificate'.

All solutions to the issues I had right after finishing the installation are in that document.

Issues solved during upgrades and previous installations are in other documents in the old notes folder.

New issues solved :

sudo -u www-data php /var/www/nextcloud/occ anything

Full Error Message :

An unhandled exception has been thrown:<br>
OCP\HintException: [0]: Memcache \OC\Memcache\APCu not available for local cache (Is the matching PHP module installed and enabled?)

01. Fix Error Memcache  OC\Memcache\APCu not available


