# vscode-like-vimrc
VimをVSCodeライクにするための.vimrcです

![vim-demo.gif](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/145075/ff490fb5-4cc2-03ca-0794-8d11959571c7.gif)

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

