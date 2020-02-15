### Install neovim
#### Linux
`curl -LO https://github.com/neovim/neovim/releases/download/stable/nvim.appimage`
or you can use the nvim.appimage in this folder
`chmod u+x nvim.appimage`
`./nvim.appimage`
###### for centos
```
yum install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
yum install -y neovim python3-neovim
# you might need python2-neovim as well on older Fedora releases
```
###### ubuntu >= 18.04
sudo apt install neovim

### Install pynvim
pip install pynvim
pip install --user pynvim (non root)
pip install --upgrade pynvim 

### Install Plug
put the plug.vim as ~/.local/share/nvim/site/autoload/plug.vim 

### costomize init.vim
copy the init.vim to ~/.config/nvim.init.vim
change let g:python3_host_prog = '/export2/home/anaconda3/bin/python' to your own python path

### Install Jedi
pip install jedi

### color 
put color/ to ~/.config/nvim/colors 

### PlugInstall
open nvim then type :PlugInstall


### Tmux
control+b :setw -g mode-keys vi 
























let g:python3_host_prog = '/full/path/to/neovim3/bin/python'
