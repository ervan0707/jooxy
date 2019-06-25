*Unofficial Joox Web API*

----

## Requirement

The jooxy module only requires Python 3. You can download from [here](https://www.python.org/downloads/). 

## Installation

Installation is simple. It can be installed from pip using the following command:
```sh
$ pip install jooxy
```
Or from the code:
```sh
$ python setup.py install
```

## Usage

```python
>>> from jooxy import *
>>> joox = Jooxy('EMAIL', 'PASSWORD')
>>> #or
>>> joox = Jooxy('EMAIL', 'PASSWORD', saveData=False)
>>> #or
>>> joox = Jooxy()
```

## Author
Ervan R.F / [@ervan0707](https://twitter.com/ervan0707)
