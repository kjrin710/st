[中文版](./docs/README_zh.md)

# st - simple terminal

## About st

st is a simple terminal emulator for X which sucks less.  
This is a personal fork of the [st](https://st.suckless.org/) project from [suckless.org](https://suckless.org/).  

### Requirements
In order to build st you need the Xlib header files.  

### Installation
Edit config.mk to match your local setup (st is installed into the /usr/local namespace by default).  

Afterwards enter the following command to build and install st (if necessary as root):  

`make clean install`  

### Running st
If you did not install st with make clean install, you must compile the st terminfo entry with the following command:  

`tic -sx st.info`  

See the man page for additional details.  

## Custom Configuration
The following personalized adjustments have been made on the basis of the original st:  

### Patch 
- alpha
- anysize
- scrollback-reflow-standalone-extended

### Appearance
- **Font**: Use `hack`, size 24
- **Theme**: Dark blue color scheme
