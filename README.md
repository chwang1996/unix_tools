## Installation of zsh 
### Install zsh ( ubuntu )

`sudo apt update`

`sudo apt upgrade`

`sudo apt install zsh`


### Install oh-my-zsh

via curl

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

via wget

`sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"`

### Using custom theme
#### Copy the custom theme to oh-my-zsh custom theme folder

`cp zsh/cus_amuse.zsh-theme ~/.oh-my-zsh/custom/themes`

#### Edit .zshrc
Change ZSH_THEME to `ZSH_THEME="cus_amuse"`

#### Install Powerline font

`sudo apt install powerline`

### Using zsh auto-suggestion
#### Copy plugin from repo
Copy the zsh/zsh-autosuggestions/ folder to ~/.zsh, if there is no ~/.zsh, create it first

`cp -r zsh/zsh-autosuggestions/ ~/.zsh`

#### Edit .zshrc
Adding `source ~/.zsh/zsh-autosuggestions/zsh-autosuggestions.zsh`


## Installation of vim
### Install vim ( ubuntu )

`sudo apt install vim`

### Setting custom vim

`cp vim/.vimrc ~/.vimrc`

`mkdir ~/.vim`

`cp -r vim/vim-autocomplpop/* ~/.vim`

