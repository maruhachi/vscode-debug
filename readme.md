# VSCodeでJavaScriptをデバッグしてみたい

## 見方
Stepとして、やりたいことの複雑さをだんだん上げていく

* step1
  * js単体として実行可能なものをその場で実行・デバッグ
* step2
  * 静的htmlから読み込むjsの挙動を確認しながらデバッグ
* step3
  * step2のjsをMinifyして実行・デバッグ
* step4
  * webpack?でjsを監視、LiveEditしながらデバッグ

* 予定
  * vue.jsをデバッグ(SourceMap?)
  * TypeScriptをデバッグ
  * Sass? PostCSSをデバッグ

## デバッグの動かし方
.vscode フォルダもコミットしている。  
デバッグの構成はステップごとに作成する。

## How to start
```
$ git clone (this repo)
$ cd vscode-debug
$ code .
```