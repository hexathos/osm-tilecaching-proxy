OSM-Tile-Caching-Proxy
======================

This file is a caching proxy script for fetching openstreetmap tiles, and
enhancing the call to respect the German Data Protection Act.

It will use your servers ip address and not the ip address of your visitors
for accessing tiles.

Place the file in a subfolder of your folder (e.g. /wp-content) and create
a folder called "tiles", make the folder read/write able.

If you are using leafletjs, change the tile layer to
<yoururl>/wp-content/tileproxy.php?s={s}&z={z}&x={x}&y={y}

Feel free to submit issues to the github issue tracker at
https://github.com/mrbendig/osm-tilecaching-proxy/issues
