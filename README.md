# keypad-input-kanata
This repo contains a WIP config for [kanata](https://github.com/jtroo/kanata) that uses the tap-dance-eager function for input macros on a Nokia 8110 4G keypad.

tap-dance-eager is not available in the current version of kanata yet, so I've
added a binary to the repo for now. One for x86_64 and one for
arm-unknown-linux-musleabi. The latter should run on the phone.

There was an issue with key 445 (phone pick/hang up) on kanata v1.2.0 that is
resolved with PR298. The corresponding binaries have been added to this repo.
