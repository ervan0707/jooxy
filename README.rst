.. contents::

Unofficial Joox Web API

**Homepage**: https://github.com/ervan0707/jooxy

Requirements
============
The linepy module only requires Python 3

Installation
============
Installation is simple. It can be installed from pip using the following
command::

    $ pip install jooxy

Or from the terminal::

    $ python setup.py install

Usage
============
::

    >>> from jooxy import *
    >>> joox = Jooxy('EMAIL', 'PASSWORD')
    >>> #or
    >>> joox = Jooxy('EMAIL', 'PASSWORD', saveData=False)
    >>> #or
    >>> joox = Jooxy()

_.