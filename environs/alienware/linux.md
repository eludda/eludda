# How to Set Up a Linux OS

Set up a minimal environment on Ubuntu. It also works on Debian, elementary OS, and similar distros.

## Terminal & Shells

Ubuntu’s default terminal is [GNOME Terminal][gnome-terminal], but [Alacritty](https://alacritty.org) works too.

Alacritty can be installed via [Snap][install-alacritty]. Run the following command:

```bash
sudo snap install alacritty --classic
```

### Installing Shells

Zsh (enhanced with [Oh My Zsh](https://ohmyz.sh)) is an excellent alternative to Bash.

Install Zsh using `apt` and set it as the default shell.

```bash
sudo apt install zsh
```

```bash
chsh -s $(which zsh)
```

Install Oh My Zsh in one line of code:

```bash
curl -fsSL https://install.ohmyz.sh | sh
```

[Starship](https://starship.rs) is ideal for minimalists and seamlessly integrates with Zsh.

Install Starship in one line of code:

```bash
curl -sS https://starship.rs/install.sh | sh
```

Add the following to the end of `~/.zshrc`.

```bash
eval "$(starship init zsh)"
```

[fish](https://fishshell.com) is a friendly interactive shell. Install it by running:

```bash
sudo add-apt-repository ppa:fish-shell/release-4
sudo apt update
```

```bash
sudo apt install fish
```

## Browser & Editor

### Google Chrome

1. Download the `.deb` file from the [download](https://www.google.com/chrome/) page.
2. Run the following command to install it.

```bash
sudo apt install ./<download>.deb
```

### Chromium

[Chromium](https://www.chromium.org/Home/) can be installed via [Snap](https://snapcraft.io/chromium).

### VS Code

[VS Code](https://code.visualstudio.com) can be installed via [Snap](https://snapcraft.io/code).

## Programming Languages

| Language | Install via Snap                   |
| -------- | ---------------------------------- |
| Node.js  | `sudo snap install node --classic` |
| Ruby     | `sudo snap install ruby --classic` |
| Go       | `sudo snap install go --classic`   |

[gnome-terminal]: https://github.com/GNOME/gnome-terminal
[install-alacritty]: https://snapcraft.io/alacritty
