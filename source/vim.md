# vimの使い方
## nvimでinit.vimの編集
vimの_vimrcはneovimだとinit.vimである。コードの書き方は全く変わらない。
```
$ cd ~/.config
$ cd nvim
$ vi init.vim
```
## 行頭に行番号を表示する
'cpoptions'にフラグ'n'が含まれていないときは、折り返された行の先頭は行番号の表示される桁に入り込まない。

```
$ set number
```
## カーソルのある行を強調する
カーソルがあるテキストを目立たせるのに便利だが、スクリーンの再描画が遅くなる。ビジュアルモードでは強調は行われない。
```
$ set cursorline
```

