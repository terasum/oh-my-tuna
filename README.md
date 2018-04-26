oh-my-tuna
==========================

`oh-my-tuna` is a script for automating using TUNA mirrors when applicable.

Usage
==========================

The simple way:

By curl

```bash
curl -o- https://rawgit.com/tuna/oh-my-tuna/master/oh-my-tuna.py | python
```

or Wget:

```bash
wget -qO- https://rawgit.com/tuna/oh-my-tuna/master/oh-my-tuna.py | python
```

Change system-wide settings instead of user-wide:
```bash
sudo oh-my-tuna.py --global
```

Get help:
```bash
python oh-my-tuna.py -h
```

Coverage
=========================
 - Anaconda
 - Arch Linux
 - CTAN
 - Debian
 - Homebrew
 - PyPI
 - Ubuntu
 - TeX Live (by tlmgr)
 
TODO
========================

 

License
==========================

Licensed under GNU General Public License 3.0
