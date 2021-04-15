These are my notes on installing Nextcloud on Raspberry Pi with Apache and Mariadb and staying green after upgrades.

The notes start at '00. Nextcloud 20.0.4 on Raspberry Pi 4 running Buster'.

All solutions to the issues I had after the installation are in that document :

    1) The PHP memory limit is below the recommended value of 512MB.
    2) The "Strict-Transport-Security" HTTP header is not set to at least "15552000" seconds. For enhanced security, it is recommended to enable HSTS as described in the security tips ↗.

    3) Your web server is not properly set up to resolve "/.well-known/caldav". Further information can be found in the documentation.
    4) Your web server is not properly set up to resolve "/.well-known/carddav". Further information can be found in the documentation.
    5) No memory cache has been configured. To enhance performance, please configure a memcache, if available. Further information can be found in the documentation.
    6) The database is missing some indexes. Due to the fact that adding indexes on big tables could take some time they were not added automatically. By running "occ db:add-missing-indices" those missing indexes could be added manually while the instance keeps running. Once the indexes are added queries to those tables are usually much faster.
        Missing index "cards_abiduri" in table "oc_cards".
    7) This instance is missing some recommended PHP modules. For improved performance and better compatibility it is highly recommended to install them.
        bcmath
        imagick

Issues solved after the installation are in subsequent documents.

I hope these notes help me to stay green in the future.
