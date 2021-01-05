# ca6fix

[ヘネパタ6版のPDF版](https://tatsu-zine.com/books/computer-architecture-6ed)を買ったらPDFとしての作りがちょっと残念だったところを修正します。

* 目次(しおり)が申し訳程度で使えない。
* 偶数ページが左、記数ページが右に来る様にレイアウトされているのに、見開き表示をすると逆に表示されてしまう。
* タイトル、著者のメタデータが入っていない。

## 使い方

```sh
$ pip3 install pypdf4
$ python3 ca6fix.sh -i (入力ファイル名) -o (出力ファイル名)
```

## ライセンス

MIT License
