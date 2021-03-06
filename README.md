# Pavol Dilung's Gentoo Linux Overlay
This is my personal Gentoo overlay where I maintain packages I create or
modify. If anything is out of date or doesn't build on your system, create
a [new issue](https://github.com/pdilung/gentoo-overlay/issues/new) and attach
a copy of the build log from a [pastebin](http://pastebin.com/).


## Installation
The easiest way to add this overlay to your Portage tree is through
__layman(8)__.

```
# emerge -av layman
# layman -a pdilung
```

## Packages

### Networking

#### UniFi Controller `net-wireless/unifi`
[UniFi Controller](http://wiki.ubnt.com/UniFi_FAQ) is a management controller
and inferface for the Ubiquiti Networks UniFi access points.

## Contributors

### net-wireless/unifi
* Foster McLane
* Ben Roberts
