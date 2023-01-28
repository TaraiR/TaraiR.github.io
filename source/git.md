# GITの使い方
SSH接続するために公開鍵と秘密鍵を生成する
```
$ ssh-keygen rsa
```
生成された`rsa-key.pub`をgithubの設定ページにコピペしてテスト
```
$ ssh -T git@github.com
```

クローンするとき
```
$ git clone repositoryURL
```
変更結果を公開するとき
```
$ git add
$ git commit -m "commit message"
$ git push
```
全部変更
```
$ git add .
```

