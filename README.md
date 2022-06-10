<h1 align="center">nvim config</h1>

### Test drive 
If you have distrobox installed:
'''
mkdir ~/.distrobox/neovim
distrobox-create --image docker.io/library/alpine:latest --name neovim --home ~/.distrobox/neovim/
mkdir ~/.distrobox/neovim/.config
distrobox-create --image docker.io/library/alpine:latest --name neovim --home ~/.distrobox/neovim/
distrobox-enter neovim
cd ~
mkdir .config
cd .config
sudo apk add git neovim
git clone https://github.com/mecattaf/nvim.git
nvim +PackerSync
'''

### Plugins

- [autopairs](https://github.com/windwp/nvim-autopairs)
- [bufferline](https://github.com/akinsho/bufferline.nvim)
- [Comment](https://github.com/numToStr/Comment.nvim)
- [friendly-snippets](https://github.com/rafamadriz/friendly-snippets)
- [gitsigns](https://github.com/lewis6991/gitsigns.nvim)
- [indent-blankline](https://github.com/lukas-reineke/indent-blankline.nvim)
- [LuaSnip](https://github.com/L3MON4D3/LuaSnip)
- [nvim-cmp](https://github.com/hrsh7th/nvim-cmp)
- [nvim-colorizer](https://github.com/norcalli/nvim-colorizer.lua)
- [nvim-tree](https://kyazdani42/nvim-tree.lua)
- [telescope](https://github.com/nvim-telescope/telescope.nvim)
- [treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
- [twilight](https://github.com/folke/twilight.nvim)
- [zen-mode](https://github.com/folke/zen-mode.nvim)
in testing:
- [leap](https://github.com/ggandor/leap.nvim)
- [repeat](https://github.com/tpope/vim-repeat)


## Keybinds

  |    Keybinds    |                Info               |
  | -----          | -----                             |
  | Tab            | Next Buffer                       |
  | Shift + Tab    | Previous Buffer                   |
  | h + s          | Open a horizontal split           |
  | v + s          | Open a vertical split             |
  | Space + v      | Open a terminal in vertical split |
  | Space + h      | Open a terminal in split          |
  | Space + t      | New tab                           |
  | Space + x      | Close Buffer                      |
  | Space + z      | Toggle Zen mode                   |
  | Space + g      | Toggle Twilight mode              |
  | Space + m      | Toggle minimal mode               |
  | Space + /      | Toggle comment                    |
  | Space + Space  | Open telescope                    |
  | f + f          | Open telescope find_files         |
  | Control + s    | Write file                        |
  | Control + n    | Toggle Nvim tree                  |
  | Control + b    | Focus Nvim tree                   |
  | Space + h      | Hard Update                       |

## References
- [Manas140](https://github.com/Manas140/Conscious)

### Also check out:
- [NvChad](https://github.com/NvChad/NvChad): Good starting point for lua Setup
- [LunarVim](https://github.com/LunarVim/LunarVim): Nvim config for front-end development
- [Nv-ide](https://github.com/crivotz/nv-ide): Nvim config for general software development
