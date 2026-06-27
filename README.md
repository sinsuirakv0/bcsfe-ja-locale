# BCSFE Japanese Locale

BCSFE-Python 用の非公式日本語ロケールです。

このロケールは AI-assisted draft として作成しています。本家 BCSFE-Python への PR や提出を目的にしたものではありません。ゲーム内の正式名称、アイテム名、細かい呼び名には仮訳が含まれる可能性があります。

## 導入方法

1. Git をインストールします。
2. BCSFE を起動します。
3. `Edit config` -> `Language` -> `Add Locale` を開きます。
4. このリポジトリの URL を `.git` 付きで入力します。
5. BCSFE を再起動します。

```text
https://github.com/sinsuirakv0/bcsfe-ja-locale.git
```

## 注意

- 非公式ロケールです。
- 本家への提出用ではありません。
- 翻訳は人間レビュー前提の下書きです。
- BCSFE の更新によりキーが追加/削除された場合、ロケール側も更新が必要です。

## 作業メモ

- `locale.json` は BCSFE の `Add Locale` と更新確認用です。
- `files/metadata.json` は BCSFE 起動時のロケール表示用です。
- `{name}` のような変数は変更しないでください。
- `{{other_key}}` のような参照は基本的に維持してください。
- `<@e>...</>` のような色タグは基本的に維持してください。
- `|` 区切りの値は、先頭が表示名、後続が入力別名として使われることがあります。
