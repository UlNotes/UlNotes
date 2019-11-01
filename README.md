# UiNotes
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/UlNotes/UiNotes?style=flat-square)
![GitHub All Releases](https://img.shields.io/github/downloads/UlNotes/UiNotes/total?style=flat-square)
![GitHub](https://img.shields.io/github/license/UlNotes/UiNotes?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/UlNotes/UiNotes?style=flat-square)
![GitHub closed issues](https://img.shields.io/github/issues-closed/UlNotes/UiNotes?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/UlNotes/UiNotes?style=flat-square)

[![forthebadge](https://forthebadge.com/images/badges/built-with-grammas-recipe.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/contains-cat-gifs.svg)](https://forthebadge.com)

The app of UiNotes
- Currently a WIP (Work In Progress)
- Currently only made for Linux, Makefile should work on Ubuntu systems

## Dependencies (Libraries)
- Python 3
- GTK+ 3.0
- WebKit2GTK+
- Boost

*You will also need any libraries required by the above libraries*
### Installing Dpendencies
#### Linux
##### Ubuntu
```bash
# Python3 should be installed by default; if not, a google search will show you the best way to get it
# GTK+ 3.0 should already be installed on Ubuntu; if not, a google search will show you the best way to get it
$ sudo apt-get install libwebkit2gtk-4.0-dev
$ sudo apt-get install libboost-dev
```

## Planned features coming soon
- [x] Open up any file
- [ ] Create a home menu for the app
- [ ] Python access to DOM
  - [ ] Clean up the code for this
  - [ ] Python can store values from JS
    - [x] Numbers
    - [x] Booleans
    - [x] Arrays
    - [ ] Functions
    - [ ] Objects

## Planned features coming eventually
- [ ] Easy cross-platform compiling for Linux (Ubuntu), Windows, and MacOS
- [ ] Make Python feel like Python instead of just a function that runs javascript

Trying to read values of char**, https://stackoverflow.com/questions/4993076/char-and-dereferencing-pointers
