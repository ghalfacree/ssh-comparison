---
title: phpseclib
homepage: http://phpseclib.sourceforge.net/
source-repository: https://github.com/phpseclib/phpseclib
license: "[MIT style](https://github.com/phpseclib/phpseclib/blob/master/LICENSE)"
#first-release:
#    date: YYYY-MM-DD
latest-release:
    version: 1.0.0
    date: 2015-08-02
changelog: https://github.com/phpseclib/phpseclib/blob/master/CHANGELOG.md
client: unknown
server: unknown
library: client

protocols:
    cipher:
        - arcfour256
        - arcfour128
        - aes128-ctr
        - aes192-ctr
        - aes256-ctr
        - twofish128-ctr
        - twofish192-ctr
        - twofish256-ctr
        - aes256-cbc
        - aes192-cbc
        - aes128-cbc
        - twofish128-cbc
        - twofish192-cbc
        - twofish256-cbc
        - twofish-cbc
        - blowfish-ctr
        - blowfish-cbc
        - 3des-ctr
        - 3des-cbc
    compression:
        - none
    hostkey:
        - ssh-rsa
        - ssh-dss
    kex:
        - diffie-hellman-group1-sha1
        - diffie-hellman-group14-sha1
        - diffie-hellman-group-exchange-sha1
        - diffie-hellman-group-exchange-sha256
    mac:
        - hmac-sha2-256
        - hmac-sha1-96
        - hmac-sha1
        - hmac-md5-96
        - hmac-md5
    userauth:
        - keyboard-interactive
        - publickey
        - password
---
* Pure PHP implementation.
