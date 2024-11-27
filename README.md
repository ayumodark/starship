# Images (battery module currently not enabled)
![img1](https://github.com/ayumodark/starship/blob/images/screenshot.png)
![img2](https://github.com/ayumodark/starship/blob/images/screenshot2.png)
# Pre-Install
- Install `starship`
- Install `nerdfont`, configure terminal to use `nerdfont`
- Install `git`

# Quick Install
```
cd ~/.config && git clone -b config --single-branch https://github.com/ayumodark/starship --depth=1 && rm -rf starship/.git && touch ~/.bashrc && echo "export STARSHIP_CONFIG=~/.config/starship/config.toml" >> ~/.bashrc && echo "eval "$(starship init bash)"" >> ~/.bashrc && exec bash
```
