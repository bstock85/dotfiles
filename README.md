# dotfiles
Set dot files utilizing stow
```
stow .
```


## nushell scripts
```
atuin init nu | save .config/nushell/autoload/atuin.nu
carapace _carapace nushell | save --force .config/nushell/autoload/carapace.nu
pixi completion -s nushell | save -f .config/nushell/autoload/pixi.nu
starship init nu | save -f .config/nushell/autoload/starship.nu
zoxide init nushell | save .config/nushell/autoload/zoxide.nu
```