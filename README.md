# Google Search for Console
コマンドラインからGoogle検索ができるアプリケーションです。
> このアプリケーションはGoogleとの関連は一切ありません

## 使い方
Google検索
```
> ggr [キーワード]
```

## ダウンロード

十分な動作確認を実施してから公開していますが、予期せぬ不具合が発生する可能性もありますので、自己責任でご利用ください。


下記のリンクよりダウンロードしてください。

https://github.com/code-raisan/Google-Search-for-Console/raw/main/build/ggr.exe

ブロックされてしまう場合はこちらでもダウンロードできます。
```
> curl https://limu.ml/daa9x -o ggr.exe
```
> ご使用には、 Microsoft .NET Framework 4.7.2 が必要になります


## PATH
このコマンドをどの場所にいても使えるようにするため、PATHを通すことをお勧めします。
> このプログラムにはPATHを通すコマンドが乗っています


まず、ダウンロードしたプログラムを適当なフォルダをつくりおいてください。(Cドライブ直下にフォルダを作成するのが分かりやすくていいと思います)

次に下記のようなコマンドをコマンドプロンプトまたはWindows PowerShellなどに打ち込んでください。
```
> [プログラムまでのパス(例 : C:￥app￥gsfc￥ggr.exe)] @add-path
```
これで成功と出ていればPATHが通っているので ` ggr [キーワード] ` が使えるかどうか試してみてください
