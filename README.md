# js-other
Used for Quality, Rush, and master proxy

Bootstrap will determine machine use, and which site(installation) to pull config from
1. password to access bootstrap (or password for github pulll etc
2. site
3. machine type (Quality screen / Rush Machine / Proxy Master)
    Quality screen will boot at load to full screen html page to a website defined by laravel config for the site
    Rush - will ask which machine to rush, and determine how many seconds to rush by, then populate the file to work
            will push the config as typed in bootstrap to laravel, and then can be modified online without ssh'ing into machine
    Proxy Master - will booat at load to https:///console.lmi-tech.co.uk
