# muzshic
Since I couldn't find the ideal playlist manager I created my own
scripts.  At the moment they're just for me but I intend to make stuff
more portable.  Requests are welcome.

## What does it look like?

![screenshot](/screenshot/screenshot.png?raw=true "That's what it looks like!")

## dependencies
 * zsh, no I am not going to rewrite this program to work with bash.
 * For the music player I recommend mpv, much nicer than mplayer
 * And diff and colordiff are nice to have as well.

So...

```zsh
apt-get install zsh mpv diffutils colordiff
```

## Install
Install? Are you crazy? Just checkout this directory somewhere, and
symlink them to somewhere in your PATH. I bet you will only really use
mkplaylist and randomsong.

## Getting started
Run in this order:
 * <code>genconfig</code>: to create an initial config, after that edit that file.
 * <code>mkplaylist</code>: to generate a "database".
 * <code>randomsong</code>: to listen to a random song.
 * <code>randomsong -L 'ride the lightning'</code>: to listen to the album Ride The Lightning.
 * <code>randomsong -h</code>: to see what else is possible.
