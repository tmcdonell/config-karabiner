Karabiner
=========

Configuration files for Karabiner, the keyboard customiser for OS X.

https://pqrs.org/osx/karabiner/

Karabiner stores the configuration in `$HOME/Library/Application Support/Karabiner/`

Karabiner-elements stores its configuration in `$HOME/.config/karabiner/karabiner.json`.

To fix key repeat rate (requires logout):

```sh
$ defaults write NSGlobalDomain InitialKeyRepeat -int 10
$ defaults write NSGlobalDomain KeyRepeat -int 1
```

