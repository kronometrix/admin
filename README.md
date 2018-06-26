# Kronometrix Authentication #

This is the authentication binary package for **Kronometrix** software.

## Modules ##
* Openresty
* Redis

## Libs ##
* lua-resty-http-simple
* lua-resty-template
* router.lua

### Required Libraries ###

FreeBSD
* openssl
* pcre

Linux
* libpcre3-dev
* libssl-dev


## Installation


#### FreeBSD 10 amd64
```
# pkg install /var/tmp//var/tmp/kauth-1.4.10-freebsd10.3-amd64.txz
Updating FreeBSD repository catalogue...
FreeBSD repository is up-to-date.
All repositories are up-to-date.
Checking integrity... done (0 conflicting)
The following 1 packages will be affected (of 0 checked):

New packages to be INSTALLED:
	kauth: 1.4.10

The process will require 29 MiB more space.

Proceed with this action? [y/N]: y
[1/1] Installing kronometrix-auth-1.0.0b49...
[1/1] Extracting kronometrix-auth-1.0.0b49: 100%
```
 
