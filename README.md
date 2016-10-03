# cordlr-color [![NPM version](https://badge.fury.io/js/cordlr-color.svg)](https://npmjs.org/package/cordlr-color) [![Build Status](https://travis-ci.org/jamen/cordlr-color.svg?branch=master)](https://travis-ci.org/jamen/cordlr-color)

> Given a hex/rgb/hsl/etc. color code, message an image of that color.

It supports anything SVG's `fill` would.

## Installation

```sh
$ npm install --save cordlr-color
```

## Usage

```
color <...codes> [--background <code>]
```

Example:
```
color #FFF
```
```
color #0F0F00 'rgba(0, 244, 100, 0.5)'
```
```
color 'rgba(0,0,0,0.8)' --background=red
```

## License

MIT © [Jamen Marz](https://github.com/jamen)