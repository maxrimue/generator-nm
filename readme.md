# generator-nmp [![Build Status](https://travis-ci.org/maxrimue/generator-nmp.svg?branch=master)](https://travis-ci.org/maxrimue/generator-nmp)

> Note: this project was originally forked from Sindre Sorhus' [generator-nm](https://github.com/sindresorhus/generator-nm) module. In contrast, it provides baked in prettier support.

> Scaffold out a node module

Optionally with a [CLI](http://en.wikipedia.org/wiki/Command-line_interface).

![](screenshot.png)

## Install

```
$ npm install --global yo generator-nmp
```

## Usage

With [yo](https://github.com/yeoman/yo):

```
$ yo nmp
```

There are multiple command-line options available:

```
$ yo nmp --help

  Usage:
    yo nmp [options]

  Options:
    --help          # Print the generator's options and usage
    --skip-cache    # Do not remember prompt answers                      Default: false
    --skip-install  # Do not automatically install dependencies           Default: false
    --org           # Publish to a GitHub organization account
    --cli           # Add a CLI
    --coverage      # Add code coverage with nyc
    --codecov       # Upload coverage to codecov.io (implies --coverage)
```

The `--org` option takes a string value (i.e. `--org=avajs`). All others are boolean flags and can be negated with the `no` prefix (i.e. `--no-codecov`). You will be prompted for any options not passed on the command-line.

## Tip

Use [chalk](https://github.com/sindresorhus/chalk) if you want colors in your CLI.

## License

MIT © [Sindre Sorhus](https://sindresorhus.com)
