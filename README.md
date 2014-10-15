# AwesomeText (VIM Colorscheme)

Distraction-free ByWord like UI for editing text documents for _GUI VIM_.
Please, see my [VIMRC][vimrc] for an example implementation.

## Screenshots

![dark](https://raw.githubusercontent.com/nikhgupta/awesome-text/master/awesome-text-dark.png)
![light](https://raw.githubusercontent.com/nikhgupta/awesome-text/master/awesome-text-light.png)

## Installation

To use the dark theme ensure `set background=dark` is present in your
`~/.vimrc` file. Otherwise Vim will use the light variation by default.

Add `colorscheme awesome-text-dark` to your `~/.vimrc` for dark theme,
and `colorscheme awesome-text-light` for light theme.

### Vundle
Add the following to your `~/.vimrc` file and run `PluginInstall` in Vim.

    Plugin 'nikhgupta/awesome-text'
    
### Pathogen

    cd ~/.vim/bundle
    git clone https://github.com/nikhgupta/awesome-text.git

### Manual

    cd ~/.vim/colors
    git clone git://github.com/nikhgupta/awesome-text.git awesome-text
    cp awesome-text/colors/*.vim .

  [vimrc]: https://github.com/nikhgupta/dotfiles/blob/master/vimrc#L1261
