# iterm2colors #

Set colorschemes in iterm2, directly from the command line.

# What it does #

Uses iterm2's escape codes (TODO: link) to set terminal colors from within the terminal.

The themes are all from http://iterm2colorschemes.com/, but aren't currently dynamically linked.

# How to use it #

Get it via antigen or oh-my-zsh

# Included commands

* `_iterm2color_apply`: Apply a colorscheme to the current terminal pane
* `_iterm2color_random`: Choose a colorscheme at random and apply it to the current terminal pane

# Default aliases

```
alias ac=_iterm2colors_apply
alias acl='echo $_iterm2colors_current'
alias acr=_iterm2colors_apply_random
```


