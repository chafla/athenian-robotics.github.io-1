# OSX Setup

## One-time Steps

Install the following pieces of software: 

### [XCode](http://developer.apple.com/xcode/)

### [Java 8](https://java.com/en/download/)

### [Homebrew](http://brew.sh)

```bash
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### [Python 2](https://www.python.org)
```bash
$ brew install python
```

### [Python 3](https://www.python.org)
```bash
$ brew install python3
```

### [pip](https://en.wikipedia.org/wiki/Pip_(package_manager))
```bash
$ sudo easy_install pip
```

### [git](https://git-scm.com)
```bash
$ brew install git
```

### [maven](http://maven.apache.org)
```bash
$ brew install maven
```

### [gradle](http://maven.apache.org)
```bash
$ brew install gradle
```

### [httpie](https://github.com/jkbrzt/httpie)
```bash
$ brew install httpie
```

### [GitKraken](https://www.gitkraken.com) or [SourceTree](https://www.sourcetreeapp.com)


## Ongoing Admin

Keep your brew-installed apps up to date with: 

```bash
$ brew update
$ brew upgrade
```

You can check on the health of your `brew` installation with:
```bash
$ brew doctor
```