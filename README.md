Hostapd
=======

Simple docker image for running [hostapd](http://w1.fi/hostapd/) in a container.

Usage
-----

The image assumes that, at the very least, the `hostapd.conf` file will be
mounted at `/srv/hostapd/etc/hostapd.conf`.  A more robust approach would be to
mount a directory at `/srv/hostapd` containing subdirectories like `etc`, `run`,  and
`log`, allowing the container to share status information with the host.
