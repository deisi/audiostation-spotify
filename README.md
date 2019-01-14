docker.io Spotifyd - Spotify Device + Remote Control
===================================================

Simple dockerfile with spotifyd. This container ist for the audiosation project. Documentation might be wrong.


Configure it
------------

Edit the `spotifyd/spotifyd.conf` to fit your needs. 
For complete configuration options, see https://github.com/Spotifyd/spotifyd


Pull the image it
--------

`docker pull audiostation/spotify`


Run it
------

Replace the variables

docker run \
     -p 6767:6767 \
      audiostation/spotifyd
```


Ports
-----

* `6767` - Spotifyd remote control server
