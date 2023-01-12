# dotHOME

My config files.

* use Hack fonts (`# doas pkg_add hack-fonts`)
* use Vim
* use i3 config file

```console
# run install.sh
```

## Vim

Extract plugins/packages into `~/dotHOME/vim/pack/${VENDOR}start`.

- [Exuberant Ctags Patterns for JavaScript](https://github.com/romainl/ctags-patterns-for-javascript)
- vim-prettier
- vimwiki
- [slimv](https://github.com/kovisoft/slimv)
- web-indent (to help indent JavaScript and CSS code in the HTML files)
- [vim-javascript](https://github.com/pangloss/vim-javascript)
- [vim-jsx-pretty](https://github.com/MaxMEllon/vim-jsx-pretty)

## TMUX Plugins

1. [tmux-resurrect](https://github.com/tmux-plugins/tmux-resurrect)

```console
$ cd # you are now in your $HOME
$ git clone https://github.com/tmux-plugins/tmux-resurrect
$ tmux source-file ~/.tmux.conf # reload TMUX environment, if TMUX already run press ^b R
```
