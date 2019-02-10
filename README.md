# tormix
<a href="https://imgur.com/gallery/zrP4rGm" target="_blank"><img src="https://i.imgur.com/3jCzXVt.png" alt="img" height="200px"/></a>

A simple TUI client for the `transmission-cli`.

- Written in `bash`.

Based on the <a href="https://github.com/dylanaraps/torque">original project</a> from <a href="https://github.com/dylanaraps">dylanaraps</a><br>
I decided to change the name (to not conflict with other existing programs) and add many more features.

## Dependencies

- `bash`
- `transmission-cli`

## Installation
This is a `bash` script, so it does not require an installation.<br><br>
Nevertheless, if you want to properly configure the `.config/tormix` directory for color support<br>
and place the script and its man page in the proper directories of `/usr`, you can run<br><br>
`./install` (it requires sudo access)<br><br>
In any case, you can always place the script where you like manually.

## Running

1. Start `transmission-daemon`.
2. Run `tormix`.

## Features
- Autocomplete of torrent ids to start, pause or remove them 
- Autocomplete of local paths to add new torrent
- Customizable color themes
- Smoother interface (as few screen redraws as possible

... More to come
