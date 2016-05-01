A collection of utilities to upload images to imgur and copy the URLs to the
clipboard.

# Upload to Imgur.workflow

## Installing to OS X

1. Double-click on the service to install it.
2. If you want, create a hotkey for the upload service in System Preferences ->
   Keyboard -> Keyboard Shortcuts -> Services.

## Usage

1. Select the image(s) that you want to upload.
2. If you've set up a hotkey for the service, push it, and you're done!
   Otherwise, click the application name in the menu bar (probably "Finder"), go
   to "Services", then click "Upload to Imgur".

# imgur

A bash script for OS X and Linux that uploads images to imgur and copies the
image URLs to the clipboard.

Usage: `imgur [filenames]`

If you don't especify any filename, they will be read from standard input. You
can either type them manually, read the list of files from a text file through
redirection or pipe the result of a command. Be brave! You can even do `ls |
imgur`! (Note: you shouldn't be that brave)

Prerequisite: `curl` Optional: `pbcopy` (included in OS X), `xsel`, or `xclip`

# Maintainer

ShyWest

# License

Creative Commons Attribution 3.0 Unported

# Release Notes

* v3.1: Support for batch uploading
* v3.0: Imgur API v3 support, and fixed a clipboard copy bug with the
  command-line tool
* v2.1: Replaced Growl notifications with OS X's
* v2.0: Much better error checking, and the OS X service has a new Growl alert
  for when the upload fails.
* v1.6: Got a unique API key for these utilities.
* v1.5: Added an OS X workflow for hotkeying the upload
* v1.1: Added a flag to disable clipboard access
* v1.0: Initial release

# Credits

* Bart Nagel <bart@tremby.net>
* Phil Tang <tangphillip@gmail.com>
* Federico Brigante <@bfred_it>
