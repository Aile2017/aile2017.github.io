# Aile2017.github.io

Aile2017 の GitHub Pages ポートフォリオサイトです。

- URL: https://aile2017.github.io/
- 内容: About / Projects / Contact を 1 ページで掲載

## Projects

### GreenPad
- Repository: https://github.com/Aile2017/GreenPad
- 概要: Windows x64 向けの軽量テキストエディタ。

### GreenPad-translations
- Repository: https://github.com/Aile2017/GreenPad-translations
- 概要:
  GreenPad の言語ファイル (.lng) を管理する翻訳リポジトリです。
  上流 6 言語（English, Japanese, Chinese Simplified/Traditional, Korean, Russian）に加えて、
  追加言語（例: French, German）を保守しています。
- 同期運用:
  GitHub Actions で upstream を日次同期し、新規キーは `[TODO]` 付きで自動挿入されます。

### libchardet
- Repository: https://github.com/Aile2017/libchardet
- 概要: 文字コード自動判定で GreenPad から利用している C/C++ ライブラリ。

### pcre2
- Repository: https://github.com/Aile2017/pcre2
- 概要: GreenPad の正規表現検索機能で利用している C ライブラリ。

## Repository Structure

```text
.
|- Aile2017.png
|- google6ea1fa549685cbc2.html
|- index.html
|- README.md
|- robots.txt
|- sitemap.xml
|- css/
|  `- style.css
|- js/
`- projects/
```

## Local Preview

静的サイトのため、`index.html` をブラウザで開けば確認できます。
必要に応じて Live Server などのローカルサーバーを使用してください。