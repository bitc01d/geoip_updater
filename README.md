# GeoIP Updater

# Credit

A have use a part of code from here: http://stackoverflow.com/questions/9628770/how-can-i-download-a-file-to-a-specific-directory

# Requirement

apt-get install geoip-database

# Info

It's a good idea to have this in a cron like this:

5 8 * * 6 python /pathto/geoip_updater.py



