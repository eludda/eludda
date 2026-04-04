# How to Set Up a MacBook

## Homebrew

[Homebrew](https://brew.sh) is a package manager for macOS.

Install Homebrew in one line of code:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```bash
sudo xcode-select --install
```

> If installation fails, manually remove the `/Library/Developer/CommandLineTools` directory and retry.

```bash
brew install zsh tree starship
brew install go deno node ruby
brew install httpie sqlite
brew install ffmpeg
```

```bash
brew tap dart-lang/dart
brew install dart
```

```bash
brew install --cask font-monoid
brew install --cask font-jetbrains-mono
```

```bash
brew install anomalyco/tap/opencode
```

[font-monoid]: https://github.com/Homebrew/homebrew-cask/blob/main/Casks/font/font-m/font-monoid.rb
[font-jetbrains-mono]: https://github.com/Homebrew/homebrew-cask/blob/main/Casks/font/font-j/font-jetbrains-mono.rb

Install Oh My Zsh in one line of code:

```bash
curl -fsSL https://install.ohmyz.sh | sh
```

```bash
curl -fsSL https://deno.land/install.sh | sh
```

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
```

```bash
nvm install 22
```

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

```bash
go install -v golang.org/x/tools/gopls@latest
```

[app-imovie]: https://apps.apple.com/cn/app/imovie-%E5%89%AA%E8%BE%91/id408981434
[app-id836500024]: https://apps.apple.com/cn/app/%E5%BE%AE%E4%BF%A1/id836500024
[app-the-unarchiver]: https://apps.apple.com/cn/app/the-unarchiver/id425424353
[app-bitwarden]: https://apps.apple.com/cn/app/bitwarden/id1352778147
[app-localsend]: https://apps.apple.com/cn/app/localsend/id1661733229
[app-xcode]: https://apps.apple.com/cn/app/xcode/id497799835
