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

# local vimrc

Used to load subdirectory specific vimrc file.

This plugin searches for local vimrc files in the file system tree of the currently opened file. By default it searches for all ".lvimrc" files from the file's directory up to the root directory and loads them in reverse order.

### Download

Click to download the package [vimball].

### Installation

Open the downloaded vimball

`vim localvimrc.vmb`

Source it using -

`:so %`

Then restart your vim.

### Some useful resources

[Localvimrc](https://www.vim.org/scripts/script.php?script_id=441)

[Github](https://github.com/embear/vim-localvimrc)

[Vundle]:http://github.com/VundleVim/Vundle.vim
[vimball]:https://www.vim.org/scripts/download_script.php?src_id=26187
