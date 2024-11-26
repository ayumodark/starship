# Pre-Install
- Install `starship`
- Install 'nerdfont', configure terminal to use nerdfont

# Quick Install
```
cd ~/.config && git clone -b main --single-branch https://github.com/ayumodark/starship --depth=1 && rm -rf starship/.git starship/README.md && touch ~.bashrc && echo "export STARSHIP_CONFIG=~/.config/starship/config.toml" && echo "eval "$(starship init bash)"" >> ~.bashrc
```
