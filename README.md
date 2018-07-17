# YouTube Music for Franz

An unofficial Franz recipe for [YouTube Music](https://music.youtube.com/).

## Installing

### Windows

With git and PowerShell:

```sh
mkdir $env:APPDATA\Franz\recipes\dev\
git clone git@github.com:badetitou/franz-youtube-music.git $env:APPDATA\Franz\recipes\dev\franz-youtube-music
```

With Explorer:

1. Download the `franz-youtube-music.zip` from github.  Extract it to its own folder (`franz-youtube-music`).
2. Open `%appdata%/Franz/recipes/dev/`.  The `dev` folder may not exist, so go ahead and create it.
3. Copy the `franz-youtube-music` folder into the plugins directory.
4. Reload Franz.

### Mac

```sh
mkdir ~/Library/Application\ Support/Franz/recipes/dev/
git clone git@github.com:badetitou/franz-youtube-music.git ~/Library/Application\ Support/Franz/recipes/dev/franz-youtube-music
```

### Linux

```sh
mkdir ~/.config/Franz/recipes/dev
git clone git@github.com:badetitou/franz-youtube-music.git ~/.config/Franz/recipes/dev/franz-youtube-music
```