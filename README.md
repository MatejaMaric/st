# About this project:

This is my fork of [st][stterm] terminal.

### Build requirements:

- Xlib header files
- fontconfig
- freetype2

### Installation

Edit `config.mk` to match your local setup (st is installed into
the `/usr/local` namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install

### Running st

If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

[stterm]: https://st.suckless.org
