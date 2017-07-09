To build the package as deb:

1. apt-get install build-essential devscripts lintian libgeoip-dev php-all-dev
2. Clone this repo
3. Switch to folder php-geoip-1.2.0
3. Run there: debuild -b -uc -us
