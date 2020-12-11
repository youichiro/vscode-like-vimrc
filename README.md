# vscode-like-vimrc
VimをVSCodeライクにするための.vimrcです

![vim-demo](https://user-images.githubusercontent.com/20487308/101944648-683f2e80-3c30-11eb-9bff-75b8e66ee5e5.gif)

## setup

```sh
# vim-plugをインストール
$ curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vimrc

# VSCodeのカラースキームをダウンロード
$ git clone https://github.com/tomasiser/vim-code-dark.git ~/.vim/bundle/vim-code-dark.git
$ ln -s ~/.vim/bundle/vim-code-dark.git/colors/codedark.vim ~/.vim/colors/codedark.vim

# Menlo Nerd Fontをインストールしてターミナルのフォントを変更
# https://github.com/yumitsu/font-menlo-extra/blob/master/Menlo-Regular-Normal.ttf

# fzf.vimで必要なパッケージをインストール
$ brew install bat
$ brew install ripgrep
```

## 参考

