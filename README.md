# CuerdOS Icon theme

This is the official icon theme for CuerdOS.

It is based on "Elementary-xfce" [https://github.com/shimmerproject/elementary-xfce] which in turn is based on "Elementary-project" [https://elementary.io/]

This fork has been made to mark the corporate colors of CuerdOS to the icon pack; in addition to the fact that the images of these icons have been converted to the indexed color model, with the aim of following the philosophy of this distribution.

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
