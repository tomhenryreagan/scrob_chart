# About

`scrob_chart` is a command line tool to generate and download Last.fm
album charts. It relies on the wonderful site
[TapMusic](https://www.tapmusic.net/) to generate the charts.

# Installation

Copy the script file `scrob_chart` to somewhere on your $PATH, e.g.
`~/.local/bin`. Make sure it is set to executable, e.g. `chmod +x
scrob_chart`. 

macOS users may wish to edit the source to change the default `OUTFILE`
value to something more macOS-friendly.

# Dependencies

`getopt`, `whoami`, `wget`, `bash`, and an Internet connection.

# License

[GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html)

# TODO

* Update default OUTFILE to work on macOS
