# 確認用テーマ (kakunin)

確認用テーマ（kakunin） は _s (underscores) https://underscores.me/ をベースに、下記ファイルに変更を加えたものです。
対策で使用するコードやスタイルはコメントアウトして記述してあります。


## style.css

* _sで用意されたCSSはすべて削除。
* 「確認用テーマの設定」を追加。


## functions.php

* 「確認用テーマの設定」を追加。
* style.cssをフロントとエディターの両方に適用するように指定。
* style.cssの編集結果をすぐに表示に反映するように指定。


## template-parts/content.php

* theme.jsonがある場合はルートコンテナ `<div class="entry-content">` に `is-layout-constrained` と `has-global-padding` クラスを追加するように指定。


## theme.json.example

* theme.jsonの記述例。

