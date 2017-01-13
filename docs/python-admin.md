# Python Administration

## Installation

### OSX

Installation details are 
[here](http://docs.python-guide.org/en/latest/starting/install3/osx/).

Python3 requires `gcc`, which you can get by installing 
 [XCode](http://developer.apple.com/xcode/) or 
[Command Line Tools](https://developer.apple.com/downloads/).

Install python3 and pip3 with:
```bash
$ brew install python3
```

## Package Management

Determine installed packages with:
```bash
$ pip3 list 
```

Determine outdated packages with:
```bash
$ pip3 list --outdated
```

Install a package with:
```bash
$ pip3 install pkg_name
```

Update a package with:
```bash
$ pip3 install --upgrade pkg_name
```

