Dotfiles
=========

These are my very opinionated dotfiles. They are just how I roll. 

  - Bash Color Scheme
  - Aliases
  - Useful functions
  - Nano Syntax Highlighting
  - Simple installer will backup old dotfiles and symlink new ones
  - Magic

Features
----
Bash

Installation
----
To install these dotfiles first clone the repository to your home directory:

```sh
cd ~
git clone https://github.com/jason-rutherford/dotfiles.git
```

Next execute the makesymlinks.sh

```sh
cd dotfiles
./makesymlinks.sh
```
That script will loop through the included dotfiles, move existing ones into ~/dotfiles_old and then create symlinks in your home directory pointing to the ~/dotfiles ones.

Thanks to
----
* Mathias Bynens for his [dotfiles](https://github.com/mathiasbynens/dotfiles)
* Michael J. Smalley for his [dotfiles](https://github.com/michaeljsmalley/dotfiles)




License
----

MIT

**Free Software, Hell Yeah!**
    