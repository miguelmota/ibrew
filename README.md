# ibrew

> A simple bash script to interactively search [Homebrew](https://brew.sh/) formulas and install them.

[![License](http://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/miguelmota/ibrew/master/LICENSE)

It's like the [ibrew](https://www.npmjs.com/package/ibrew) NPM package, but not taking up your disk space with node_modules.

## Demo

<img src="./assets/screencast.gif" width="500" />

## Install

```bash
wget https://raw.githubusercontent.com/miguelmota/ibrew/master/ibrew.sh -O ibrew.sh
chmod +x ibrew.sh
mv ibrew.sh /usr/local/bin/ibrew
```

## Usage

```bash
$ ibrew {search-term}
```

## Example

```bash
$ ibrew say

Searching for "say"...
Select formula to install:
  1  cowsay
  2  ponysay
  3  possatti/possatti/pokemonsay
Select option #: 1
Installing formula cowsay...
```

## License

[MIT](LICENSE)

