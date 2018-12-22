# Poppin
パスワード管理のDBアプリケーション  

本プロダクトのドキュメントを[gitbook](https://github.com/GitbookIO/gitbook)で提供する

## Requirements
gibook
  - node: v10.14.2
  - npm: 6.4.1
  - gitbook-cli: 2.3.2

## Getting Started
リポジトリのclone

    $ git clone https://github.com/amenoci/poppin

### ドキュメント
pluginのインストール

    $ cd poppin/
    $ gitbook install docs/

## Usage
### ドキュメント
ドキュメントサーバの起動

    $ cd poppin/
    $ gitbook serve docs/

上記コマンドでgitbookのドキュメントサーバが起動するので, http://localhost:4000 でアクセス可能

ドキュメントの生成

    $ cd poppin/
    $ gitbook build docs/ [path/to/your/dest/]

- 生成先（path/to/your/dest/）を指定しない場合は`docs/_book/`に生成される
