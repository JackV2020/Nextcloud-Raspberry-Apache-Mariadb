These are my notes on installing Nextcloud on Raspberry Pi Buster with Apache and Mariadb and staying green after upgrades.

The last succesfull installation is in '00. Nextcloud 24.0.6 on Raspberry Pi 4 running Buster'.

All solutions to the issues I had after finishing the installation are in that document.

Issues solved during upgrades and previous installations are in other documents.

I stopped creating '00. Nextcloud.....' documents for earlier upgrades. I only created issue documents.

Note that hidden things like '04. Web Trashcan not available after delete big file.txt' can come back after each upgrade.

I hope these notes help me and you to stay green in the future.

For the time being 24.0.6 is my last and final version because I run on a 32 bit Raspberry Pi. You can check that by running lshw ( after 'sudo apt install lshw' )

    '00. Nextcloud 20.0.4 on Raspberry Pi 4 running Buster.txt'
    '00. Nextcloud 22.0.0 on Raspberry Pi 4 running Buster.txt'
    '00. Nextcloud 22.2.3 on Raspberry Pi 4 running Buster.txt'
    Not a real success : '00. Nextcloud 22.x.y on Raspberry Pi 4 running Bullseye.txt'
    '00. Nextcloud 24.0.6 on Raspberry Pi 4 running Buster.txt'
    '01. When adding a Windows client hangs.txt'
    '02. Need user quota different than suggestions in dropdown box.txt'
    '03. Tuning maximum file size.txt'
    '04. Web Trashcan not available after delete big file.txt'
    '05. The database is missing some indexes.txt'
    '06. The database is missing some primary keys.txt'
    '07. Some columns in the database are missing a conversion to big int.txt'
    '08. File locked for delete.txt'
    '09. .ocdata” error in Overview screen.txt'
    '10. we have detected multiple invalid login attempts from your ip. therefore your next login is throttled up to 30 seconds.txt'
    '11. Host-Prefix according to scan.nextcloud.com .txt'
    '12. Your installation has no default phone region set.txt'
    '13. Module php-imagick in this instance has no SVG support.txt'
    '14. Some jobs haven’t been executed since.....txt'
    '15. A background job is pending that checks for user imported SSL certificates.txt'
    '16. webfinger and nodeinfo message like caldav and carddav.txt'
    '17. can not be downloaded because of local file name clash.txt'
    '18. Background job ran long time ago.txt'
    '19. PHP version 7.3 upgrade to 8.0.txt'
    'xx. notes from previous versions.txt'
    'OK. Oke, nice to know.txt'
