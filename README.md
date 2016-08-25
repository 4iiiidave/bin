# bin

Random shell scripts

## app-icon

Create all iOS icon variations from a master image

    > app-icon [icon.png]


## json

A simple JSON-formatter. Reads from `stdin`, prints to `stdout`.

## garmin

Copies all `.fit` files from a mounted [Garmin](http://explore.garmin.com/en-US/edge/) device to `~/Dropbox/bike/fit` and then ejects the device

## os

A simple script to echo one of the following identifiers to `stdout` based on OS name:

 * `osx` - [Mac OS X](http://www.apple.com/osx/)
 * `raspberry` - [Raspbian](http://www.raspbian.org)
 * `?` - Anything else

## gitutil

Open the remote host for a git repository in your web browser of choice. Currently supports [GitHub](https://github.com) & [BitBucket](https://bitbucket.org).

    > gitutil [filename]

## quit

Quit an OS X application by name:

  * `> quit Terminal`
  * `> quit "Google Chrome"`
