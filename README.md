# gal

Yet another photo gallery generator.

[Demo page](http://pics.niedzwiedzinski.cyou/mando/)

## Why?

I could not find any other working solution that would be as simple as this. This script just resizes all images and generates grid menu for them. That is all.

## Install

```
git clone https://git.niedzwiedzinski.cyou/gal && cd gal
export BINDIR=$HOME/scripts
ln -s $PWD/gal $BINDIR
```

## Usage

```
nix shell github:19pdh/gal

gal [PHOTOS DIR] [OUTPUT DIR]
```
