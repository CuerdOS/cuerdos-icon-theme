# CuerdOS Icon theme

This is an icon-theme maintained with Xfce in mind, but it should work on other desktops like Gnome3 as well.

It is a fork of the upstream [elementary-xfce] (https://github.com/newhoa/elementary-xfce) which in turn is a fork of [elementary project](http://elementary.io). The reason for forking was that the project decided to focus on its own desktop environment and dropped a ton of (ugly, but necessary) symlinks. This icon-theme is supposed to keep everything working, but gets updates from upstream occasionally.

We'd like to encourage you to not only consider contributing to this, but also to the original icon-set.

## Installation

You can use the Makefile to install the theme locally (default prefix is /usr/local).

### Build dependencies
- optipng
- GTK3

### Installation for the current user only (without admin privileges)

```
./configure --prefix=$HOME/.local
make
make install
make icon-caches
```

### Installation for all users

```
./configure
make
sudo make install
sudo make icon-caches
