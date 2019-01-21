# vimrc

### Set up [Vundle]

` git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

### Configure Plugins

Put this at the top of your `.vimrc` to use Vundle.

```vim
set nocompatible
filetype off
set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()
Plugin 'VundleVim/Vundle.vim'

" All of your Plugins must be added before the following line
call vundle#end()            
filetype plugin indent on
" To ignore plugin indent changes, instead use:
" filetype plugin on

" Put your non-Plugin stuff after this line
```

### Install Plugins

Launch `vim` and run `:PluginInstall`
To install from command line: `vim +PluginInstall +qall`

[Vundle]:http://github.com/VundleVim/Vundle.vim
