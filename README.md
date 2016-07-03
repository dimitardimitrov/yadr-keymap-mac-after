# yadr-keymap-mac-after

The [skwp/dotfiles](https://github.com/skwp/dotfiles#installation) dotfiles repo has a mapping file for MacVim. Unfortunately, all of the mappings use \<D-...\> (Command Key) which does not work in iTerm2 or terminal in general. The yadr-keymap-mac-after file changes the mapping of \<D-...\> to \<C-...\>. This is not the most confortable key, but it works. I welcome suggestions for a better mapping for mac. 

### Installation
There are several ways to install as described in the [swkp documents](https://github.com/skwp/dotfiles/blob/master/doc/vim/keymaps.md). This is my preferred method:
  1. Clone the repository:

        git clone --recursive git@github.com:dimitardimitrov/yadr-keymap-mac-after.git [your directory]

  2. Link the file in skwp/dotfiles:

        ln -s [your directory]/yadr-keymap-mac-after.vim [your_path]/.yadr/vim/after/plugin/yadr-keymap-mac-after.vim

You will have to restart any Vim sessions that you had open prior to the installation. Also, this will leave your .yadr repo with an uncommited yadr-keymap-mac-after.vim file in it. This will not be a problem unless you want to update the dotfiles with their newest version. In that case, stash the uncommited file, pull from the skwp/dotfiles repo to update and re-apply the file from the stash.


