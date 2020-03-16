# List and Tips for Programs in Linux

# Index
- [Terminal](#terminal)
- [Screen recorder](#screen-recorder)
- [Edit video](#edit-video)

## Terminal
```bash
sudo apt-get install -y  zsh
chsh -s `which zsh`
wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

## Screen recorder

Open Broadcaster Software (OBS)

```bash
sudo add-apt-repository ppa:obsproject/obs-studio
sudo apt update
sudo apt install obs-studio
```

## Edit video

[Shotcut](https://www.shotcutapp.com/download/)


