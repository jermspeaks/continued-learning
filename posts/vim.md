# Vim

## Initial Setup

I got into vim from a co-worker.
I thought it's that clunky text editor in your terminal you must use when you have ssh into the linux server.
However, I've grown to understand vim is much more than a text editor.
It can also be an IDE.

When I first used vim, it just looked plain an boring.
The black screen with hard to understand shortcuts.
There weren't any line numbers.
I didn't even know how to exit the damn program for a good 5 minutes.

Then I started figuring it out slowly.
Vim has different modes.
Vim can do macros.
Vim can find things with the same grep commands.
And it's quite expandable with the limitless plugins.
Vim is an endless rabbithole where you will get sucked in hours just setting it up.
But it's your customization.
And that's the beauty of vim.

Best advice - configure vim, and for that matter dotfiles, on your own. Don't blindly copy and paste configurations, because you'll never understand them all. 

### Modal Editing

Quoted from Nick Nisi

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
- [vim-markdown](https://github.com/plasticboy/vim-markdown) - markdown syntax, matching rules and mappings, and extensions

### Packages

- [Sparkup](https://github.com/rstacruz/sparkup) - For html tag completion

### Colorize

I'm currently using Monokai, mainly because it was a default I had with Ruby on sublime. 
I set it up using [vim-monokai](https://github.com/sickill/vim-monokai), which I actually want to go back and figure out how to hook it up with vundle and have it linked to the repo.

I want to figure out how to do this better, so I placed a todo with the wiki from the vim wikia.

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

