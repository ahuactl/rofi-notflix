<h1 align="center">webtorrent-rofi</h1>

A rofi client for scraping.

> Watch BugsWriters video on it - [bugswriter's notflix](https://youtu.be/RFJCL9C46Mc)

### How does this work?

This is a shell script. It scrapes 1337x and gets the magnet link.
After this it uses [webtorrent](https://webtorrent.io/) to stream the video from the magnet link.
For scraping, the script uses simple gnu utils like sed, awk, paste, cut.

## Usage

```bash
webtorrent-rofi
webtorrent-rofi [query]
```

## Requirements

* [webtorrent](https://webtorrent.io/) - A tool to stream torrent.
* [rofi](https://github.com/davatorium/rofi) - A window switcher, Application launcher and dmenu replacement.

```console
# npm install webtorrent-cli -g
# pacman -S rofi
```

## Installation

```console
# curl -sL "https://raw.githubusercontent.com/ahuactl/webtorrent-rofi/master/webtorrent-rofi" -o /usr/local/bin/webtorrent-rofi
# chmod +x /usr/local/bin/notflix
```
- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply run `sudo rm -f /usr/local/bin/webtorrent-rofi`.

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).
