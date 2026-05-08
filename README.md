# install pixi
```
curl -fsSL https://pixi.sh/install.sh | sh
echo 'export PATH="~/.pixi/bin:$PATH"' >> ~/.bashrc 
```

# pixi packages install
```
pixi global install atuin bat btop carapace dua-cli fastfetch helix gh git lazydocker lazygit nushell starship stow tealdeer yazi zellij zoxide
pixi global update
```

# Set dot files utilizing stow
```
stow .
```

## nushell scripts
```
atuin init nu | save .config/nushell/autoload/atuin.nu -f
carapace _carapace nushell | save --force .config/nushell/autoload/carapace.nu -f
pixi completion -s nushell | save -f .config/nushell/autoload/pixi.nu -f
starship init nu | save -f .config/nushell/autoload/starship.nu -f
zoxide init nushell | save .config/nushell/autoload/zoxide.nu -f
```
