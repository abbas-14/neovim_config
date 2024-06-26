# This repo contains the neovim configuration (esp. for developers).

## Requirements:

- neovim installed
- connected to the internet.
- python3 installed
- Linux / MacOS / WSL

## do the following steps

- copy the contents into ~/.config/nvim/ folder

## If you want to setup for rust development then

- open the neovim in a terminal
- enter this command
    ```
        :MasonInstall rust-analyzer codelldb
    ```
## if you want to enable other languages as well then add language server names in `~/.config/nvim/lua/v10/plugin_config/treesitter.lua` file. Also check for the documentation of `treesitter` plugin

## Possible Errors:

- while openning first time, just press the enter key repeatidily until you see all the things being setup. For next times there will be no such errors or warnings.
- if getting vimspector issue saying the neovim needs to be compiled with python3, then issue the following command in the terminal:
    ```
        pip3 install neovim
    ```
- after installing the neovim python package, you need to reopen the nvim to see the effect.
