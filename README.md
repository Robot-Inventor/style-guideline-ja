# style-guideline-ja

日本語の文章を書くときのスタイルガイドラインです。

ガイドラインそのものは[クリエイティブ・コモンズ 表示 4.0 国際 ライセンス](http://creativecommons.org/licenses/by/4.0/)の下に提供されています。

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>

また、presetフォルダー内にある、校閲ツールの設定ファイルはMITライセンスで利用できます。

## プリセットについて

このリポジトリーには、textlintとprh設定ファイルが含まれています。

textlintは次のルールをインストールする必要があります。

- [textlint-rule-preset-ja-spacing](https://github.com/textlint-ja/textlint-rule-preset-ja-spacing)
- [textlint-rule-preset-ja-technical-writing](https://github.com/textlint-ja/textlint-rule-preset-ja-technical-writing)
- [textlint-rule-spellcheck-tech-word](https://github.com/azu/textlint-rule-spellcheck-tech-word)
- [textlint-rule-preset-japanese](https://github.com/textlint-ja/textlint-rule-preset-japanese)
- [textlint-rule-no-dropping-i](https://github.com/textlint-ja/textlint-rule-no-dropping-i)
- [textlint-rule-no-insert-dropping-sa](https://github.com/textlint-ja/textlint-rule-no-insert-dropping-sa)
- [textlint-rule-preset-JTF-style](https://github.com/textlint-ja/textlint-rule-preset-JTF-style)
- [@textlint-ja/textlint-rule-no-synonyms](https://github.com/textlint-ja/textlint-rule-no-synonyms)
- [textlint-rule-no-insert-re](https://github.com/textlint-ja/textlint-rule-no-insert-re)
- [textlint-rule-no-duplicated-bunmatsu-hyougen](https://github.com/textlint-ja/textlint-rule-no-duplicated-bunmatsu-hyougen)
- [textlint-rule-period-in-list-item](https://github.com/textlint-rule/textlint-rule-period-in-list-item)
- [textlint-rule-prefer-tari-tari](https://github.com/textlint-ja/textlint-rule-prefer-tari-tari)
- [textlint-rule-no-mixed-zenkaku-and-hankaku-alphabet](https://github.com/textlint-ja/textlint-rule-no-mixed-zenkaku-and-hankaku-alphabet)

すべてインストールするには、次のコマンドを実行します。

```
npm install textlint-rule-preset-ja-spacing textlint-rule-preset-ja-technical-writing textlint-rule-spellcheck-tech-word textlint-rule-preset-japanese @textlint-ja/textlint-rule-no-dropping-i @textlint-ja/textlint-rule-no-insert-dropping-sa textlint-rule-preset-jtf-style @textlint-ja/textlint-rule-no-synonyms sudachi-synonyms-dictionary @textlint-ja/textlint-rule-no-insert-re textlint-rule-no-duplicated-bunmatsu-hyougen textlint-rule-period-in-list-item textlint-rule-prefer-tari-tari textlint-rule-no-mixed-zenkaku-and-hankaku-alphabet
```

## 目次

- [スペースについて](guidline/spacing.md)
- [全体について](guidline/overall.md)
- [単位などについて](guidline/unit.md)
- [カタカナについて](guidline/katakana.md)
- [表記ゆれについて](guidline/spelling_inconsistency.md)
- [開く漢字](guidline/hiraku.md)
- [閉じるひらがな](guidline/tojiru.md)
