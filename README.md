Dotfiler: OSX configs
=====================

[![changelog](http://allmychanges.com/p/dotfiles/svetlyak40wt-osx/badge/)](http://allmychanges.com/p/dotfiles/svetlyak40wt-osx/?utm_source=badge)

This repository contains my emacs configs, based on Emacs Starter Kit.
It's purpose to be used as a repository for [dotfiler][].

For convinience, don't copy these files into you homedir. Instead,
go and install [dotfiler][], then clone this repository, using
`dot add <url>` command and run `dot update` to make all necessary
symlinks.

Keybindings
-----------

This package includes two useful keybindings available in OSX
application: `Ctrl-w` and `Ctrl-u`. First backwards delete one word,
latter — deletes entire line. These keybinding works in most
system's text inputs and emulate command line behaviour.

Thanks to [Armin Ronacher][armin] for [the idea][armins-config].

[dotfiler]: https://github.com/svetlyak40wt/dotfiler
[armin]: https://twitter.com/mitsuhiko
[armins-config]: https://github.com/mitsuhiko/dotfiles/blob/master/osx/DefaultKeyBinding.dict
