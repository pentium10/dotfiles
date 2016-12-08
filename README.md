Getting Started
---------------
one liner
* `git clone git://github.com/pentium10/dotfiles ~/.dotfiles;cd ~/.dotfiles;chmod +x install;./install;screen -R;`

or steps:

* `git clone git://github.com/pentium10/dotfiles ~/.dotfiles`
* `cd ~/.dotfiles`
* `chmod +x install`
* `./install` (or `make install`)
* `screen -R`

If you `clone` to a non-standard location a.k.a not `$HOME/.dotfiles` be sure
to edit `bash/bashrc.symlink` and update the `DOTFILES` variable.

License
-------
Copyright (c) 2013, Pentium10

Everything is provided **as-is** under the **MIT** license. For more information,
see *LICENSE*.
