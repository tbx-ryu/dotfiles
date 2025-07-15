### tmux

tpmをインストールし、sourceで.tmux.confを読み込む  

```shell
cd ~
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
wget https://raw.githubusercontent.com/tbx-ryu/dotfiles/refs/heads/main/Ubuntu/.tmux.conf -P ~/ # Ryukiの.tmux.confのダウンロード
source .tmux.conf
```


### Terminal

Gnome-Terminalの設定アプリをインストールし、その中でdircolorの設定アプリもインストールする。

```shell
cd ~
sudo apt-get install dconf-cli
git clone https://github.com/aruhier/gnome-terminal-colors-solarized.git
cd gnome-terminal-colors-solarized
./install.sh
# 指示に従いインストールを進める
echo "eval `dircolors ~/.dir_colors/dircolors`" >>.bashrc
```
