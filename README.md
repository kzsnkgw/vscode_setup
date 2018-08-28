# vscode_setup

Visual Studio Coode の初期設定。

## インストール

[公式サイト](https://code.visualstudio.com/) よりダウンロード

## 基本設定 (User Settings)

ユーザー、ワークスペース設定は環境に合わせてお好みで。


### 設定

* Windows/Linux - File > Preferences > Settings

* macOS - Code > Preferences > Settings

## 拡張機能 一括インストール

コマンドプロント(Windows) またはターミナル(mac) で下記を実行

```sh

$ cd extensions/
$ sh install_extensions.sh

```

※ macはターミナルで `code` コマンドを実行できるよう下記手順を取る
https://qiita.com/naru0504/items/c2ed8869ffbf7682cf5c

## 拡張機能のエクスポート

```sh

$ code --list-extensions > extensions

```

### 参考

* Visual Studio Code で必要な拡張パッケージを一括でインストールするスクリプト
  https://qiita.com/busonx/items/43705af9fa864cf3bc18
