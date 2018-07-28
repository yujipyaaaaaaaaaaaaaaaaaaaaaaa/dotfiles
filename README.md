# これは何？

開発環境のvimrcやbashrcなどを置いたリポジトリです。 
自分用説明書も兼ねています。 

# 使い方

ホームディレクトリで実行する場合
```
$ git clone https://github.com/yujipyaaaaaaaaaaaaaaaaaaaaaaa/dotfiles
$ ln -s ~/.bashrc ~/dotfiles/.bashrc
$ ln -s ~/.vimrc ~/dotfiles/.vimrc
```
lnのリンク先とファイル先の順番逆かも(誤差だよ誤差

# vimのショートカット覚書



# mtuxのコマンド覚書

んなもんググれって感じ

## コマンド

```
$ tmux
$ tmux ls
$ tmux attach -t 0
$ tmux detach -t 0
$ tmux kill-session -t 0
```

## ウィンドウ
新規ウィンドウ : C-b + c 
ウィンドウ切り替え : C-b * 0 
ウィンドウ削除 : C-b + & 

## ペイン分割
水平分割 : C-b + " 
垂直分割 : C-b + % 
ペイン移動 : C-b + q, C-b + o 
ペイン削除 : C-b + x 
