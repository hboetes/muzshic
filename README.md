# muzshic
Since I couldn't find the ideal music player I created my own scripts.
At the moment they're just for me but I intend to make stuff more portable.
Requests are welcome.

## What does it look like?

![screenshot](/screenshot/screenshot.png?raw=true "That's what it looks like!")

## dependencies
 * zsh, no I am not going to rewrite this program to work with bash.
 * For the music player I recommend mpv, much nicer than mplayer
 * And diff and colordiff are nice to have as well.

## Install
Install? Are you crazy? Just checkout this directory somewhere, and
symlink them to somewhere in your PATH. I bet you will only really use
mkplaylist and randomsong

## Getting started

Run in this order:
 * genconfig: To create an initial config, and edit that file.
 * mkplaylist: to generate a "database"
 * randomsong: to listen to a random song
 * randomsong -L 'ride the lightning': to listen to the album Ride The Lightning.
 * randomsong -h: to see what else is possible.
