# git-toolbelt-zsh (WIP)

This plugin provides completion definitions for most of the commands defined by [git-toolbelt](https://github.com/nvie/git-toolbelt).

To use it with antigen, add this line to your .zshrc file:

```zsh
antigen bundle  wstein/git-toolbelt-zsh 
```

## Setup notes

The completions work by augmenting the `_git` completion provided by `zsh`. This only works with the `zsh`-provided `_git`, not the `_git` provided by `git` itself. If you have both `zsh` and `git` installed, you need to make sure that the `zsh`-provided `_git` takes precedence.

### OS X Homebrew Setup

**NOTE:** this may not work on current Homebrew distributions of git. 
