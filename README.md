# NeoVim Settings #

First, install NeoVim if you haven't already. You can follow this guide: https://www.linode.com/docs/guides/how-to-install-neovim-and-plugins-with-vim-plug/ 


Clone this repo:

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


To upload your local changes to the repo, run `get_current.sh` to copy your local `.nvimrc` and `.config/nvim/init.vim` to this directory.
