# keypad-input-kanata
This repo contains a WIP config for [kanata](https://github.com/jtroo/kanata) that uses the tap-dance-eager function for input macros on a Nokia 8110 4G keypad.

tap-dance-eager is not available in the current version of kanata yet, so I've
added a binary to the repo for now. One for x86_64 and one for
arm-unknown-linux-musleabi. The latter should run on the phone. However, it
doesn't recognize the keyboard yet.

The current config imitates the behavior of keys 0-9 on KaiOS. The other buttons
aren't mapped yet.

