# :yin_yang: Teaser Site Template for CoderDojo Conferences like [DojoCon](https://dojocon.coderdojo.jp/) / [DecaDojo](https://decadojo.coderdojo.jp/)

[![Screenshot](https://github.com/coderdojo-japan/dojocon-template.coderdojo.jp/blob/main/img/screenshot.gif?raw=true)](https://dojocon-template.coderdojo.jp/)

<br>

## :wrench: Ruby / Python / Node.js / PHP で動かす方法

### 共通

下記の手順でサーバーが無事立ち上がったら [`index.html`](https://github.com/coderdojo-japan/dojocon-template.coderdojo.jp/blob/main/index.html) を修正し、[http://localhost:8080/](http://localhost:8080/) にアクセスして修正内容を確認します。

### Ruby で動かす方法

```shell
# Ruby がインストールされていることを確認する (無ければインストールする)
$ ruby --version

# ローカルサーバーを立ち上げる
$ ruby -run -e httpd
```

<br>


### Python で動かす方法

```shell
# Python がインストールされていることを確認する (無ければインストールする)
$ python --version

# ローカルサーバーを立ち上げる
$ python -m SimpleHTTPServer 8080
```

<br>


### Node.js で動かす方法

```shell
# Node.js の npx がインストールされていることを確認する (無ければインストールする)
$ npx --version

# ローカルサーバーを立ち上げる
$ npx http-server
```

<br>


### PHP で動かす方法

```shell
# PHP がインストールされていることを確認する (無ければインストールする)
$ php --version

# ローカルサーバーを立ち上げる
$ php -S localhost:8080
```

<br>


## :octocat: 関連リポジトリ

- [GitHub - DojoCon Japan リポジトリ一覧](https://github.com/search?q=org%3Acoderdojo-japan%20dojocon&type=repositories)
- [GitHub - CoderDojo Japan organization](https://github.com/coderdojo-japan) (approved by [GitHub for Nonprofit](https://news.coderdojo.jp/2019/08/29/github-for-nonprofit/))

<br>

<div id='license'></div>

## :handshake: Credits & Works

- :yin_yang: The CoderDojo logo in header - See the [CoderDojo Charter](https://coderdojo.jp/charter).
- :camera_flash: The CoderDojo object in footer is crafted by [DojoCon Japan 2016](https://dojocon2016.coderdojo.jp/) team and photo by [@yasulab](https://github.com/yasulab).
- :art: This template is based on the [DojoCon Japan 2023](https://dojocon2023.coderdojo.jp/)'s teaser site, designed by [@kwaka1208](https://github.com/kwaka1208).

Other than the logo and photo above, the source codes, such as HTML and CSS, are published under [The MIT License](https://github.com/coderdojo-japan/teaser-template.coderdojo.jp/blob/main/LICENSE.md). Feel free to refer, copy, or share them.

-----

Copyright ©  [DojoCon Japan](https://dojocon.coderdojo.jp/) & [CoderDojo Japan](https://github.com/coderdojo-japan)
