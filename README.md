# Vim Awesome

Customized to be awesome by default. It is improved to be used on Mac OS X and
MacVim. 

If used with [MacVim](https://code.google.com/p/macvim/) you will get SublimeText-like shortcuts:

* `cmd + p` -> go to anything (via [ctrlp.vim](https://github.com/kien/ctrlp.vim))
* `cmd + /` -> toggle comment (via [nerdcommenter](https://github.com/scrooloose/nerdcommenter))
* `cmd + z` -> undo
* `cmd + shift + z` -> redo
* `cmd + [` -> indent 
* `cmd + ]` -> unindent
* `cmd + f` -> search files
* `cmd + <number>` -> jump to tab 1, tab 2, ...
* `cmd + alt + left` -> move to next tab
* `cmd + alt + right` -> move to previos tab

Some awesome features:

* Full featured autocompletion (via [YouCompleteMe](https://github.com/Valloric/YouCompleteMe))
* Automatic closing of quotes, parenthesis, brackets, etc (via [delimitMate](https://github.com/Raimondi/delimitMate))
* Splitting a window will put the new window right or below of the current one.
* Easily switch between splits with `ctrl + h,j,k,l`.
* Does not create files like `.swp`.
* Searching will always center on the line it's found in.
* Search by default incase sensitive, however if you use uppercase character
  incase sensitive search is ignored.

## Install & Update

Be sure you are using the latest **OS X 10.8**. Just clone the repo and execute
`make`:

    git clone --recursive https://github.com/fatih/vim-awesome.git
    cd vim-awesome
    make

This will create a symlink from these folder to `~/.vim` and `~./vimrc`.
Thus you can put this folder in your favorite place, move it around without any
problems. And finally you can always update it easily with:

    cd vim-awesome
    git pull origin master

## Uninstall

This will just remove the symlinks created previously:

    cd vim-awesome
    make clean

## Improvements (TODO)

* Freeze base plugins (aka add them as non submodules)
* Add Linux-compatible option
* Integrate snippet system ([SnipMate](https://github.com/garbas/vim-snipmate),
  [UltiSnip](https://github.com/SirVer/ultisnips))
* Make it compatible with [vim-sensible](https://github.com/tpope/vim-sensible)?
* Make it always as simple as possible without breaking any plugins. Users
  should add plugins theirself.
* Might integrate nerdtree, vim-sessions, etc...
* Reopen closed buffer, window or tab ...

## License

Same as VIM license. For more info see `:help license`.
