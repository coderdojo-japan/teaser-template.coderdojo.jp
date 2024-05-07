# DojoCon Japan Template for Teaser Site

![Screenshot](https://github.com/coderdojo-japan/dojocon-template.coderdojo.jp/blob/main/img/screenshot.webp?raw=true)

<br>

## :gem: ローカル環境で確認する方法

エラーなどで困ったら [Rails Girls インストール・レシピ](https://railsgirls.jp/install)を見るのがオススメです。  
Ruby がインストールできれば十分で、 **Rails のインストールは不要** です。

```shell
# macOS の場合: Homebrew ( https://brew.sh/index_ja ) 経由がオススメ
$ brew install rbenv ruby-build

# Linux の場合: https://github.com/rbenv/rbenv#readme に沿って rbenv をインストール
$ sudo apt install rbenv   # Debian, Ubuntu 系のディストリビューションの場合

# Windows の場合: 以下の Rails Girls インストール・レシピに沿ってインストール
# https://railsgirls.jp/install

# `.ruby-version` ファイルにあるバージョン番号を確認し、バージョン番号 x.y.z をメモする
# https://github.com/coderdojo-japan/dojocon.coderdojo.jp/blob/main/.ruby-version

# 上記でメモした Ruby のバージョン番号をインストールする
$ rbenv install x.y.z

# 上記のバージョンの Ruby がインストールされたことを確認する
$ ruby --version

# 必要なライブラリをインストールする
$ bundle install

# ローカルサーバーを立ち上げる
$ bundle exec jekyll server
```

無事にローカルサーバーが立ち上がったら、[http://localhost:4000/](http://localhost:4000/) にアクセスしてWebサイトを修正・確認します。

<br>


## :octocat: 関連リポジトリ

- [GitHub - DojoCon Japan リポジトリ一覧](https://github.com/search?q=org%3Acoderdojo-japan%20dojocon&type=repositories)

<br>

-----

Copyright ©  [DojoCon Japan](https://dojocon.coderdojo.jp/) & [CoderDojo Japan](https://github.com/coderdojo-japan)
