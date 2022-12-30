st - simple terminal
--------------------

This is a fork of the excellent st terminal emulator for X which sucks less.

The original source code can be found here: https://git.suckless.org/st  
The original README can be found here: [README](./README)

Changes
-------

Besides setting some opinionated defaults, I've also added these patches:

* https://st.suckless.org/patches/font2/
* https://st.suckless.org/patches/colorschemes/

Requirements
------------

* Hack Nerd Mono - https://www.nerdfonts.com/font-downloads
* Symbola (used by the default config) - https://fontlibrary.org/en/font/Symbola

Configuration
-------------

If you want to use the default config, just `rm config.h` and `make clean install`. You'll need to set ownership of the new `config.h` to yourself or edit with `sudo`.
