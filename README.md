# NeoVim Settings #

First, clone the repo:

```
git clone git@github.com:jwvogt/nvim-settings.git
```

Then, run these commands:

```
cp nvim-settings/.nvimrc ~/.nvim

mkdir -p .config/nvim/
cp nvim-settings/init.vim ~/.config/nvim/init.vim
```

Alternatively, you can just run `init.sh`, but be careful because this will overwrite your current `~/.nvimrc` and `~/.config/nvim/init.vim` files.

Open NeoVim with `nvim` and run the following editor commands:

```
:source ~/.nvimrc
:PlugInstall
```
