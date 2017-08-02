[![Build Status](https://travis-ci.org/samuelbetio/clipboard.svg?branch=master)](https://travis-ci.org/samuelbetio/clipboard) [![Build Status](https://drone.io/github.com/samuelbetio/clipboard/status.png)](https://drone.io/github.com/samuelbetio/clipboard/latest) 

[![GoDoc](https://godoc.org/github.com/samuelbetio/clipboard?status.svg)](http://godoc.org/github.com/samuelbetio/clipboard)

# Clipboard for Go

Provide copying and pasting to the Clipboard for Go.

Download shell commands at https://drone.io/github.com/samuelbetio/clipboard/files

Build:

    $ go get github.com/samuelbetio/clipboard

Platforms:

* OSX
* Windows 7 (probably work on other Windows)
* Linux, Unix (requires 'xclip' or 'xsel' command to be installed)


Document: 

* http://godoc.org/github.com/samuelbetio/clipboard

Notes:

* Text string only
* UTF-8 text encoding only (no conversion)

TODO:

* Clipboard watcher(?)

## Commands:

paste shell command:

    $ go get github.com/samuelbetio/clipboard/cmd/gopaste
    $ # example:
    $ gopaste > document.txt

copy shell command:

    $ go get github.com/samuelbetio/clipboard/cmd/gocopy
    $ # example:
    $ cat document.txt | gocopy



