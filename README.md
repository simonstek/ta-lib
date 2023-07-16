# TA-Lib - Technical Analysis Library
How to generate configure from configure.ac? Steps:

```
sudo libtoolize --force
sudo aclocal
sudo autoheader
sudo automake --force-missing --add-missing
sudo autoconf
sudo ./configure
```

refrence: https://askubuntu.com/questions/27677/cannot-find-install-sh-install-sh-or-shtool-in-ac-aux
