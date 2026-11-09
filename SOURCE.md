# 出典

出典：デジタル庁デザインシステムウェブサイト https://design.digital.go.jp/dads/

- `references/dads/` は、公式配布の「デジタル庁デザインシステムβ版サイト ドキュメント（Markdown）2026年10月21日版」（`dads-markdown-20261021.zip`）を、変更せずに展開したものです。
- `references/tokens/` は、デジタル庁が公開する `@digital-go-jp/design-tokens` 2.1.0（MIT License、Copyright (c) 2023 デジタル庁、https://github.com/digital-go-jp/design-tokens ）の `dist/tokens.css`・`dist/tokens-simple.css`・`LICENSE` を、変更せずに写したものです。
- `SKILL.md`、`README.md`、`README.en.md` は、デジタル庁デザインシステムウェブサイト https://design.digital.go.jp/dads/ をもとに capsrock が作成しました。

`references/dads/` には、W3C の Web Content Accessibility Guidelines（WCAG、W3C 勧告）の達成基準名や技法名などの日本語訳が含まれます。これらの翻訳はウェブアクセシビリティ基盤委員会（WAIC、https://waic.jp/ ）によるもので、条件は https://waic.jp/license-for-translated-documents/ に従います。正式版は W3C サイト（https://www.w3.org/TR/WCAG22/ ）の英語版です。Copyright © World Wide Web Consortium.

このスキルは非公式のもので、デジタル庁が作成・承認したものではありません。

利用条件は `references/dads/introduction/notices/index.md`（公式: https://design.digital.go.jp/dads/introduction/notices/ ）に従います。

## 更新のしかた

公式のリソースページ https://design.digital.go.jp/dads/resources/ に新しい版の zip が出たら、`references/dads/` を丸ごと入れ替え、`SKILL.md` の早見表の値と日付を確かめ直します。

トークンは自動では更新されません。新しい版が出たら https://www.npmjs.com/package/@digital-go-jp/design-tokens のパッケージから `references/tokens/` の3ファイルを入れ替え、`SKILL.md` と `SOURCE.md` の版番号を直します。
