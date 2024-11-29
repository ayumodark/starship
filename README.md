# Image
soon
# Pre-Install
- Install `starship`
- Install `nerdfont`, configure terminal to use `nerdfont`
- Install `git`

# Quick Install
```
cd ~/.config && git clone -b config --single-branch https://github.com/ayumodark/starship --depth=1 && rm -rf starship/.git && touch ~/.bashrc && echo "export STARSHIP_CONFIG=~/.config/starship/config.toml" >> ~/.bashrc && echo "eval "$(starship init bash)"" >> ~/.bashrc && exec bash
```
