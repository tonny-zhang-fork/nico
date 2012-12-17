# Documentation of nico

Good to know you are here.

-----------------

nico is built on nodejs, which means you have to install nodejs. I believe you have installed nodejs, but I'd like to repeat this part.

You can download the package on [nodejs.org](http://nodejs.org) or through a package manager like apt-get and homebrew.

We will need node-gyp to compile c module, and it will trouble Windows Users. If you are on a Windows, please check <https://github.com/TooTallNate/node-gyp>, and install the missing requirements.

After the installation, maybe you have to deal with the environment variables. Linux & Mac user just editor your shell rc file (.bashrc or .zshrc):

```
export NODE_PATH="/usr/local/share/npm/lib/node_modules"
export PATH="$PATH:/usr/local/share/npm/bin"
```

The path may be wrong, correct it according to your own environment.

And Windows User should add `NODE_PATH` to your computer environment, maybe it's:

```
NODE_PATH = C:\Users\{{username}}\AppData\Roaming\npm\node_modules
```

## Installation

Install nico is simple with npm:

```
$ npm install nico -g
```

Please install it with ``-g`` option, otherwise you can't use it in command line.

If you want a live reload feature, you have to install socket.io by yourself:

```
$ npm install socket.io -g
```


## Theme


## Writing


## Configure


## Developer Guide

Actually the code of nico is easy to understand.


## Bug Report

I keep an issue tracker at [GitHub](https://github.com/lepture/nico/issues),
you can report bugs by [openning a new issue](https://github.com/lepture/nico/issues/new).
If you want any help, please contact <lepture@me.com>, English and Chinese are acceptable.