# How to Set Up a Linux OS

Set up a minimal environment on Ubuntu. It also works on Debian, elementary OS, and similar distros.

## Terminal & Shells

Ubuntu’s default terminal is [GNOME Terminal][gnome-terminal], but [Alacritty](https://alacritty.org) works too.

Alacritty can be installed via [Snap](https://snapcraft.io/alacritty).

Install [Oh My Zsh](https://ohmyz.sh).

```bash
sudo apt install zsh
curl -fsSL https://install.ohmyz.sh | sh
```

```bash
chsh -s $(which zsh)
```

Install [Starship](https://starship.rs).

```bash
curl -sS https://starship.rs/install.sh | sh
```

Add the following to the end of ~/.zshrc:

```bash
eval "$(starship init zsh)"
```

Install [fish](https://fishshell.com).

```bash
sudo add-apt-repository ppa:fish-shell/release-4
sudo apt update
```

```bash
sudo apt install fish
```

## Browser & Editor

### Google Chrome

### Chromium

Install via [Snap](https://snapcraft.io/chromium).

```bash
sudo snap install chromium
```

### VS Code

Install via [Snap](https://snapcraft.io/code).

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
