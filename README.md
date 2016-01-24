A collection of utilities to upload images to imgur and copy the URLs to the clipboard.

# Upload to Imgur.workflow

## Installing to OS X

1. Double-click on the service to install it.
2. If you want, create a hotkey for the upload service in
   System Preferences -> Keyboard -> Keyboard Shortcuts -> Services.

## Usage

1.  Select the image(s) that you want to upload.
2. If you've set up a hotkey for the service, push it, and you're done!  
Otherwise, click the application name in the menu bar (probably "Finder"),
    go to "Services", then click "Upload to Imgur".

# imgur

A bash script for OS X and Linux that uploads an image to imgur and copies 
the image URL to the clipboard.

Usage: `imgur <filename>`

Imgur will print the URL, and put the delete page's URL on stderr. If
you're on a Mac or have xsel/xclip, the image URL will also be copied
to the clipboard.

Prerequisite: `curl`
    Optional: `pbcopy` (included in OS X), `xsel`, or `xclip`

<table>
<tr>
    <th>Maintainer:</th>
    <td> Phil Tang &lt;tangphillip@gmail.com&gt;</td>
</tr>
<tr>
    <th>Last Change:</th>
    <td> 2016 Jan 24, v3.0</td>
</tr>
<tr>
    <th>License:</th>
    <td> Creative Commons Attribution 3.0 Unported</td>
</tr>
<tr>
    <th>Release Notes:</th>
    <td> v3.0: Imgur API v3 support, and fixed a clipboard copy bug with the command-line tool
        <br>v2.1: Replaced Growl notifications with OS X's
        <br> v2.0: Much better error checking, and the OS X service has a new Growl alert for when the upload fails.
        <br> v1.6: Got a unique API key for these utilities.
        <br> v1.5: Added an OS X workflow for hotkeying the upload
        <br> v1.1: Added a flag to disable clipboard access
        <br> v1.0: Initial release</td>
</tr>
<tr>
    <th>Credits:</th>
    <td> Bart Nagel &lt;bart@tremby.net&gt;
        <br> Federico Brigante &lt;@bfred_it&gt;</td>
</tr>
</table>
