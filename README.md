
# Setup

## Terminal

### Linux

Assuming [AUR package manager](https://github.com/polygamma/aurman)

```bash
aurman -S hyper
```

### MacOS

```bash
brew update
brew cask install hyper
```

## Font 

### Linux / MacOS

```bash
brew tap caskroom/fonts
brew cask install font-fira-code
```

### Windows

```bash
choco install firacode
```

## NeoVim

_Note, you may get typescript warnings if you don't have `npm i -g typescript` installed globally._

Keybindings:

* Leader `<space>`
* Switching buffers `Tab`, `Shift + Tab`, `LEADER LEADER` (last opened tab), `LEADER b`(fuzzy find)
* Fuzzy find file `LEADER f`
* Grep `Leader g`
* Sneak `f`, `F`, `s` (2 char), `S`(2 char)

### MacOS

```bash
brew install neovim
pip3 install neovim
```

### Linux

```bash
sudo apt-get install neovim
```

### Windows

```bash
choco install neovim
```

## Tmux

### Linux / MacOS

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

---

Install plugins with `Ctrl + b, I` (Best to do after all steps in README are completed)

## Fish Shell

### Linux / MacOS

```bash
brew install fish
curl -L https://get.oh-my.fish | fish
```

And follow the prompts.

## Link dotfiles

### Linux / MacOS

```bash
ln -si ./.hyper.js ~/.hyper.js
ln -si ./.tmux.conf ~/.tmux.conf
ln -si ./.init.vim ~/.config/nvim/init.vim
ln -si ./config.fish ~/.config/fish/config.fish
```

### Windows

_... use Windows Subsystem Linux and follow above instructions? :)_

