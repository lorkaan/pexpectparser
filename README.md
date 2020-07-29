# Pexpect Parser

A parser using the parsegrammar library to 
create automated bots for command line programs.

## Examples

An example of this code can be found in the following projects:
- VPN Bot
	- [Github](https://github.com/lorkaan/vpnBot)

# Installation

Pip installation is reccommended
```
pip install -u pexpectparser
```

Or if you are using PipEnv
```
pipenv shell
pipenv install pexpectparser
```

# Usage

## Import
```
import pexpectParser as pp
```

## Creating Class
```
parser = pp.Parser(<Grammar>)
```

where <Grammar> is a Grammar Object from the Parse Grammar Library.

# Dependencies

This project has the following dependencies:
- Parse Grammar Library
	- [Github](https://github.com/lorkaan/parsegrammar)
	- [Pypi](https://pypi.org/project/parsegrammar/)
	
