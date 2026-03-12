# How to Set Up a Linux OS

Set up a minimal environment on Ubuntu. It also works on Debian, elementary OS, and similar distros.

## Terminal

Ubuntu’s default terminal is [GNOME Terminal][gnome-terminal]—but [Alacritty](https://alacritty.org) also works.

Alacritty can be installed via [Snap][snapcraft].

```bash
sudo snap install alacritty --classic
```

Shells recommended for productivity:

**Oh My Zsh** - [ohmyz.sh](https://ohmyz.sh)

```bash
sudo apt install zsh
curl -fsSL https://install.ohmyz.sh | sh
```

```bash
chsh -s $(which zsh)
```

**Starship** - [starship.rs](https://starship.rs)

```bash
curl -sS https://starship.rs/install.sh | sh
```

Add the following to the end of ~/.zshrc:

```bash
eval "$(starship init zsh)"
```

**fish** - [fishshell.com](https://fishshell.com)

```bash
sudo add-apt-repository ppa:fish-shell/release-4
sudo apt update
```

```bash
sudo apt install fish
```

## Browser

- [**Google Chrome**](https://www.google.com/chrome/) — the most popular browser.
- [**Chromium**](https://www.chromium.org/Home/) — the open-source alternative to Google Chrome.

Install [Chromium](https://snapcraft.io/chromium):

```bash
sudo snap install chromium
```

## Editor

- [**VS Code**](https://code.visualstudio.com)

Install [Code](https://snapcraft.io/code):

```bash
sudo snap install code --classic
```

## Programming Languages

| Language | Install via Snap                   |
| -------- | ---------------------------------- |
| Node.js  | `sudo snap install node --classic` |
| Ruby     | `sudo snap install ruby --classic` |
| Go       | `sudo snap install go --classic`   |

[gnome-terminal]: https://github.com/GNOME/gnome-terminal
[snapcraft]: https://snapcraft.io
