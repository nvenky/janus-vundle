#Janus Vundle

This vim config repo uses all the plugins mentioned in [Janus](https://github.com/carlhuda/janus/) but uses [Vundle VIM plugin](https://github.com/gmarik/Vundle.vim.git) to install bundles/plugins instead of relying on Submodules.


##Setting up your VIM

1. Install MacVIM by running

    ````
    brew install macvim
    ````

2. Install Vundle to manage the VIM plugins that makes it awesome

    ````
    git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
    ````

3. Copy the .vimrc and .vimrc-after to your home directory.

4. Open mvim and run command

    ````
    :PluginInstall
    ````


##NOTE

All the plugins to be installed are listed in *.vimrc* file. I have customized the mapLeader key to , (comma) but you can edit it in .vimrc-after file.
