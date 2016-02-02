# clog

A [conventional](https://github.com/ajoslin/conventional-changelog/blob/a5505865ff3dd710cf757f50530e73ef0ca641da/conventions/angular.md) changelog for the rest of us

![Screenshot](other/screenshot.png)

This is just an npm distribution of the amazing [clog](https://github.com/clog-tool/clog).
[I](https://twitter.com/kentcdodds) created this package because I think `clog` is awesome and I think this is an easier
way to distribute it.

# Installation and Requirements

## Requirements

### Mac

Right now, this package only supports the `clog` distribution available for Mac. There are
[other distributions available](http://wod.twentyfives.net/bin/clog/).

### Node & npm

This is distributed as an `npm` package (some say that stands for "Node Package Manager"). So you must have Node.js (or io.js) and npm installed.

Here are quick instructions on how to get those: http://blog.nodeknockout.com/post/65463770933/how-to-install-node-js-and-npm

Congratulations, you've opened your life to a whole new world of awesome tooling and other cool things :-)

## Installation

Install this tool via `npm`: `$ npm install -g clog-cli`

# Usage

In your terminal, simply type `clog --help` to get output of the options available.

See the official [clog](https://github.com/clog-tool/clog) website for documentation on how to use `clog`.

Here's the output when you type `clog`:

```
clog v0.7.0
a conventional changelog for the rest of us

USAGE:
	clog [FLAGS] [OPTIONS]

FLAGS:
        --from-latest-tag    use latest tag as start (instead of --from)
    -h, --help               Prints help information
        --major              Increment major version by one (Sets minor and patch to 0)
        --minor              Increment minor version by one (Sets patch to 0)
        --patch              Increment patch version by one
    -v, --version            Prints version information

OPTIONS:
        --from <from>                    e.g. 12a8546
    -o, --outfile <outfile>              Where to write the changelog (Defaults to 'changelog.md')
    -r, --repository <repository>        e.g. https://github.com/thoughtram/clog
        --link-style <style>             The style of repository link to generate, defaults to github [values: Github, Gitlab, Stash]
        --subtitle <subtitle>            e.g. crazy-release-title
        --to <to>                        e.g. 8057684 (Defaults to HEAD when omitted)
        --setversion <ver>               e.g. 1.0.1
```

# LICENSE

Both this package and the `clog` tool itself are MIT licensed.
