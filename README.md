# neovim-python
neovim-python

# Prerequisites
Neovim: https://neovim.io/
NVchad: https://github.com/NvChad/NvChad

# How to use

To install this for your neovim configuration

```
# remove previous config
$ mv ~/.config/nvim ~/.config/nvim.backup
$ rm -rf ~/.local/share/nvim/
$ git clone git@github.com:jabhishek87/neovim-python.git ~/.config/nvim/lua/custom
```

Then open up neovim and let everything install.

Restart Neovim and install the treesitter syntax

```
:MasonInstallAll
```

```
:TSInstall python
```
