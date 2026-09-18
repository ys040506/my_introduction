# my_introduction

1つの Markdown ファイルを GitHub Pages で公開する自己紹介サイトです。

## 普段の更新

**`index.md` だけを編集してください。** 保存して GitHub に push すると、GitHub Pages が HTML に変換して公開します。GitHub 上で `index.md` を編集してコミットしても更新できます。

冒頭の `---` で囲まれた部分で名前・紹介文・アイコンを設定します。

```yaml
---
layout: default
title: Yuu Shimizu
description: Software, Data and Research
avatar: /my_profile_picture.jpg
---
```

`layout: default` はそのままにしてください。`avatar` の画像はプロフィールアイコンとブラウザのタブのアイコンに使われます。

以降は通常の Markdown です。`## 見出し`、箇条書き、`[表示名](URL)`、画像、表、コードブロックが使えます。セクションは自由に追加・削除できます。メールアドレスと外部リンクは仮のため、ご自身のものに差し替えてください。

## 初回の公開設定

1. このフォルダを GitHub のリポジトリに push します。
2. リポジトリの `Settings` → `Pages` を開きます。
3. `Source` を `Deploy from a branch` にします。
4. `Branch` を `main`、フォルダを `/(root)` にして保存します。
5. ビルドが完了すると、表示された URL でサイトを確認できます。

GitHub Pages 標準の Jekyll を使用します。`.nojekyll` は追加しないでください。リポジトリ名を含む公開 URL でも画像・CSS が読み込まれる構成です。

## サイトの構成

- `index.md`: 公開する内容。日常の編集はこのファイルだけです。
- `my_profile_picture.jpg`: プロフィール画像。
- `_layouts/default.html`: Markdown を囲む共通レイアウト。
- `styles.css`: 表示スタイル。
- `_config.yml`: GitHub Pages の変換設定。

HTML は公開時に生成されます。ローカルでは `index.md` をエディタの Markdown プレビューで確認できます。実際のレイアウトは GitHub Pages で確認してください。
