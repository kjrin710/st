[中文版](./docs/README_zh.md)

# st - simple terminal

## About This Fork

This is a personal fork of the [st (simple terminal)](https://st.suckless.org/) project from [suckless.org](https://suckless.org/).

**Original Source:**  https://git.suckless.org/st/  
**Original Project:**  https://st.suckless.org/

### Applied Patches and Modifications

- Add some patches
- Custom color scheme

## About st

st is a simple terminal emulator for X which sucks less.

### Requirements
In order to build st you need the Xlib header files.

### Installation
Edit config.mk to match your local setup (st is installed into the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if necessary as root):

    make clean install

### Running st
If you did not install st with make clean install, you must compile the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

## Credits

### Original Project
The st project is developed by the suckless community. See the LICENSE file for the full list of contributors.
