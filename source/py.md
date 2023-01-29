# Python の使い方
## WSLでpython環境を作る
wsl2 にはpythonが既にインストールされている。標準パッケージマネージャーpipと仮想環境の作成と管理のためにvenvを追加でインストールしなければならない。  
pythonのバージョンの確認
```
$ python3 --version
```
pythonのアップデートを行うためにwslのバージョンを更新する
```
$ sudo apt update
$ sudo apt upgrade
```
pythonの更新
```
$ sudo apt upgrade python3
```
pipのインストール
```
$ sudo apt install python3-pip
```
venvのインストール
```
$ sudo apt install python3-venv
```

## 仮想環境の作成
仮想環境の構築を行い、プロジェクトのツールを分離することで、他のプロジェクト用のツールとの間でバージョン管理上の競合を避けることができる。
プロジェクト用ディレクトリの作成
```
$ mkdir cnn
```
プロジェクト用のディレクトリに移動後、仮想環境を作成する。
```
$ python3 -m venv .venv
```
仮想環境をアクティブにする。
```
$ source .venv/bin/activate
```
成功すると、コマンドプロンプトの前に(.venv)と表示される。
仮想環境を非アクティブにするには次のコマンドを入力する。
```
$ deactivate
```


[Windowsでのpythonを利用したWEB開発](https://learn.microsoft.com/ja-jp/windows/python/web-frameworks)
