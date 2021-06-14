# mojikiban

- [ベースレジストリ](https://github.com/code4fukui/BaseRegistry)の文字で使用する、[文字情報基盤](https://moji.or.jp/mojikiban/)のJavaScriptライブラリ
- [文字情報定義ファイル](https://github.com/code4fukui/CharacterInformation)を元にした[JIS X 0213](https://github.com/code4fukui/BaseRegistry/blob/main/%E7%94%A8%E8%AA%9E.md#jis-x-0213)のJavaScriptライブラリ

## application

- [漢字検索、異体字検索](https://code4fukui.github.io/mojikiban/)
- [MJ縮退デモ](https://code4fukui.github.io/mojikiban/shrink.html)
- [JIS X 0213チェッカーβ](https://code4fukui.github.io/mojikiban/jisvalidator.html)

## UCS未定義文字

19漢字重複あり

```
MJ003718・MJ003719は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ006064・MJ006065は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ014004・MJ014005は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ029825・MJ029826は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ029893・MJ029894は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ033215・MJ033216は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ035886・MJ035887は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ037229は、図形的な差異が大きく戸籍統一文字番号: 146930に対応しないものと判断した。このため、「戸籍統一文字番号」、「対応するUCS」の値を削除するとともに、今後は国際標準化提案を行わない。Ver.005.01よりVer.004.03で対応していた戸籍統一文字番号: 146930に対応する新しいMJ文字図形名はMJ068077となる。
MJ037903・MJ037904は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ037909・MJ037910は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ040281・MJ040282は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ040579は、MJ040580と同一の字形としてデザインされていた。このため、「戸籍統一文字番号」、「対応するUCS」の値を削除する。Ver.005.01よりVer.004.03で対応していた戸籍統一文字番号: 227070に対応する新しいMJ文字図形名はMJ068082となる。また、この字形を使用する場合にはMJ040580(U+246FC)に変更することが強く推奨される。
MJ041325・MJ041326は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ041469・MJ041470は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ042077は、図形的な差異が大きく戸籍統一文字番号: 257160に対応しないものと判断した。このため、「戸籍統一文字番号」、「対応するUCS」の値を削除するとともに、今後は国際標準化提案を行わない。Ver.005.01よりVer.004.03で対応していた戸籍統一文字番号: 257160に対応する新しいMJ文字図形名はMJ068085となる。
MJ043218・MJ043219は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ053025・MJ053026は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ055352・MJ055353は、戸籍統一文字において、同一字形であり、字義も同一の内容である。
MJ059043は、MJ059042と同一の字形となっており、戸籍統一文字番号:499580に対応していなかった。このため、戸籍統一文字番号:499580に対応する新たなMJ文字図形名:MJ068101をVer.005.02において追加した。
```
