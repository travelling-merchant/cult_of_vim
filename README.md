# setup our conform nvim config

I decided to make it a seperate repo since I use it on mac and linux

## create directories

```bash
mkdir ~/.config/nvim
mkdir ~/.config/nvim/doc
mkdir ~/.config/nvim/lua
mkdir ~/.config/nvim/lua/custom
mkdir ~/.config/nvim/lua/custom/plugins
mkdir ~/.config/nvim/lua/kickstart
mkdir ~/.config/nvim/lua/kickstart/plugins
```
## symlinks

```bash
ln -s ~/cult_of_vim/nvim/README.md ~/.config/nvim/README.md
ln -s ~/cult_of_vim/nvim/init.lua ~/.config/nvim/init.lua
ln -s ~/cult_of_vim/nvim/lazy-lock.json ~/.config/nvim/lazy-lock.json
ln -s ~/cult_of_vim/nvim/doc/kickstart.txt ~/.config/nvim/doc/kickstart.txt
ln -s ~/cult_of_vim/nvim/doc/tags ~/.config/nvim/doc/tags
ln -s ~/cult_of_vim/nvim/lua/custom/plugins/init.lua ~/.config/nvim/lua/custom/plugins/init.lua
ln -s ~/cult_of_vim/nvim/lua/kickstart/health.lua ~/.config/nvim/lua/kickstart/health.lua
ln -s ~/cult_of_vim/nvim/lua/kickstart/plugins/debug.lua ~/.config/nvim/lua/kickstart/plugins/debug.lua
ln -s ~/cult_of_vim/nvim/lua/kickstart/plugins/indent_line.lua ~/.config/nvim/lua/kickstart/plugins/indent_line.lua
ln -s ~/cult_of_vim/nvim/lua/kickstart/plugins/lint.lua ~/.config/nvim/lua/kickstart/plugins/lint.lua

```

## setup for cursed os named windows.....

```shell
mkdir ~\AppData\Local\nvim
mkdir ~\AppData\Local\nvim\doc
mkdir ~\AppData\Local\nvim\lua
mkdir ~\AppData\Local\nvim\lua\custom
mkdir ~\AppData\Local\nvim\lua\custom\plugins
mkdir ~\AppData\Local\nvim\lua\kickstart
mkdir ~\AppData\Local\nvim\lua\kickstart\plugins

```

```cmd
mklink "%UserProfile%\AppData\Local\nvim\README.md" "%UserProfile%\cult_of_vim\nvim\README.md"
mklink "%UserProfile%\AppData\Local\nvim\init.lua" "%UserProfile%\cult_of_vim\nvim\init.lua"
mklink "%UserProfile%\AppData\Local\nvim\lazy-lock.json" "%UserProfile%\cult_of_vim\nvim\lazy-lock.json"
mklink "%UserProfile%\AppData\Local\nvim\doc\kickstart.txt" "%UserProfile%\cult_of_vim\nvim\doc\kickstart.txt"
mklink "%UserProfile%\AppData\Local\nvim\doc\tags" "%UserProfile%\cult_of_vim\nvim\doc\tags"
mklink "%UserProfile%\AppData\Local\nvim\lua\custom\plugins\init.lua" "%UserProfile%\cult_of_vim\nvim\lua\custom\plugins\init.lua"
mklink "%UserProfile%\AppData\Local\nvim\lua\kickstart\health.lua" "%UserProfile%\cult_of_vim\nvim\lua\kickstart\health.lua"
mklink "%UserProfile%\AppData\Local\nvim\lua\kickstart\plugins\debug.lua" "%UserProfile%\cult_of_vim\nvim\lua\kickstart\plugins\debug.lua"
mklink "%UserProfile%\AppData\Local\nvim\lua\kickstart\plugins\indent_line.lua" "%UserProfile%\cult_of_vim\nvim\lua\kickstart\plugins\indent_line.lua"
mklink "%UserProfile%\AppData\Local\nvim\lua\kickstart\plugins\lint.lua" "%UserProfile%\cult_of_vim\nvim\lua\kickstart\plugins\lint.lua"

```
