# sv-cli

CLI tool to build Small Victories sites locally.

[Homepage](https://www.smallvictori.es) |
[Twitter](https://twitter.com/smvico)

## Installation

### Install script

### Homebrew (OS X)

Homebrew can be installed via [brew.sh](http://brew.sh)

```
$ brew install sv
```

### Zip Archives (OS X, Linux, Windows)

Bare zip archives per release version are available at https://github.com/smallvictories/sv-cli/releases/

## Quickstart

First you must create a folder with an `_sv_settings.txt` file which has a `theme` attribute.

```
theme: html
```

Then run `sv`

```
$ sv start
```

You can then view your site at http://localhost:2015

SV will automatically watch for changes and rebuild your site.
