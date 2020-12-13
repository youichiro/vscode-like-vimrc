# vscode-like-vimrc
VimをVSCodeライクにするための.vimrcです

![vim5.gif](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/145075/613aa205-b99f-32c2-4bc3-18b9622ab1af.gif)

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

