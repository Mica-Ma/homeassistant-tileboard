
These are some HA and TileBoard configs so I don't lose them.

* config.js  = TileBoard addition to HA, my page layout
* configuration.yaml = HA config file
* runit - bash script to start up HA in docker
* vdscards.yaml - HA configs in yaml format

To install:

* create a config dir with 'configuration.yaml' in it for HA
* create a config/www/local/tileboard dir with TileBoard in it
* start up the container

To test:

* HA screen is at http://x.x.x.x:8123/
* TileBoard screen is at http://x.x.x.x:8123/local/tileboard/index.html

Tiles change color and icons based on state:

* example [home sreen](home-screen.png) with a door open
* press the red tile to get the [sub-screen](sub-screen.png) with 'which' door is open

