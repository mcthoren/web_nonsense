leafmap.html:

* this is basically a collection of the leaflet map examples strung together into a simple map. so far it has a few layers, a scale, zoom, and when you click it shows you the lat/long. the nice leaflet ppl can be found here: https://leafletjs.com/

* the layers are all from open and free sources.

* the layer sources and leaflet lib are all grabbed over https.

* the layer sources and leaflet lib are all IPv6 capable.

* i created this cuz i get tired of clicking thru Google's 27 different steps to opt out of their data collection, and openstreetmap tiles don't load too well thru ssh -D tunnels for me.

* TODO: i still haven't figure out how to make it automatically fill the full window yet.

poldirad_loop.html

* this is a cut down webpage of a gif of the local weather radar from the nice people here: http://www.pa.op.dlr.de/poldirad/

* i made this cuz i like looking at weather radars, and i wanted a simple small page i could leave running on an old phone plugged into a charger.

* unfortunately, it doesn't update all that often. they seem to run it when there is interesting weather about, sometimes.

dwd_rad_loop.html

* this is a cut down webpage that displays weather radar gifs for both germany and bavaria. the data and gifs are from https://www.dwd.de/DE/leistungen/radarbild_film/radarbild_film.html

* this was made on the idea that i could just pop it up on a raspberry pi or old phone or whatever in the background.
