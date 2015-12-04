# Vim

## Initial Setup

Honestly, the vim editor looks slim. But that's because I didn't know about it's different modes. That's the beauty of vim.

Best advice - configure vim, and for that matter dotfiles, on your own. Don't blindly copy and paste configurations, because you'll never understand them all. 

### Modal Editing

> Change the meaning of the keys in each mode of operation

> - Normal mode - navigate the structure of the file
> - Insert Mode - editing the file
> - Visual mode - highlighting portions of the file to manipulate at once
> - Ex mode - command mode

### Line Numbers

Where are my line numbers? Simply type the following.

`:set number`

To remove the numbers, you can use this command.

`:set nonumber` 

## Configuration

Configuration file: `~/.vimrc`

## Useful Shortcuts

All of the shortcuts can be found on the [Vim Wiki Website](http://vim.wikia.com/wiki/Vim_Tips_Wiki)

### Navigation

* `h` for left
* `l` for right
* `j` for down
* `k` for up
* `gg` top of the file
* `H` top of the window
* `ctrl + e` move window down one line
* `ctrl + y` move window up one line

### Word Manipulation

* `w` to go forward to the beginning of next word
* `b` to go backward to the beginning of previous word
* `e` to go forward to the end of the next word
* `dw` delete word up to the cursor including space between next word
* `diw` delete word on cursor

#### Yanking Words

* `yiw` yank in word

### Line Manipulation

* `0` or `^` for beginning of line
* `dd` for delete line where cursor is on
* `:m <line number>` move to line number

### Editing

* `u` for undo

### Colon Commands

* `:help <command>` for help on any command

## Plugins

Vim, like other text editors, has an ecosystem of plugins. 

- [vundle](https://github.com/VundleVim/Vundle.vim) - plugin manager
- [nerdtree](https://github.com/scrooloose/nerdtree) - file tree
- [ctrlp](https://github.com/kien/ctrlp.vim) - Fuzzy file finder
- [fugitive](https://github.com/tpope/vim-fugitive) - git tool
- [syntastic](https://github.com/scrooloose/syntastic) - syntax checker/linter

### Packages

- [Sparkup](https://github.com/rstacruz/sparkup) - For html tag completion

### Colorize

- Todo: http://vim.wikia.com/wiki/Turn_on_syntax_coloring_in_Mac_OS_X

## Macros

q{register}
(do the things)
q

### Registers

`WIP`

## More Research to go through

- http://yannesposito.com/Scratch/en/blog/Vim-as-IDE/
- coloring vim (as stated above)
- adding more language support
- adding line numbers
- go to top of file (shortcut)
- go to bottom of file (shortcut)
- how to find
- Macros: q command, recording so you don't repeat yourself

## Helpful Resources

- [vim + tmux](https://www.youtube.com/watch?v=5r6yzFEXajQ) - Talk at [OMG!Code](http://code.omahamakergroup.org/) given by [Nick Nisi](http://nicknisi.com/)

