# BCSFE Japanese Locale

BCSFE-Python 用の非公式日本語ロケールです。

このロケールは AI-assisted draft として作成しています。本家 BCSFE-Python への PR や提出を目的にしたものではありません。

## 導入方法

1. Git をインストールします。Gitのインストール方法は下にあります。
3. BCSFE を起動します。
4. `Edit config` -> `Language` -> `Add Locale` を開きます。
5. このリポジトリの URL を `.git` 付きで入力します。
6. BCSFE を再起動します。

```text
https://github.com/sinsuirakv0/bcsfe-ja-locale.git
```

## 注意

- 非公式ロケールです。
- 本家への提出用ではありません。。
- BCSFE の更新によりキーが追加/削除された場合、ロケール側も更新が必要です。

## Git のインストール方法

Windows

1. Git for Windows をインストールします。
2. インストーラーは基本的にデフォルト設定のままで問題ありません。
3. インストール後、コマンドプロンプトまたは PowerShell で以下を実行し、バージョンが表示されれば完了です。

git --version

---

macOS

Homebrew を利用する場合（推奨）

brew install git

Homebrew がない場合

Xcode Command Line Tools をインストールします。

xcode-select --install

インストール後、以下で確認します。

git --version

---

Linux

Debian / Ubuntu

sudo apt update
sudo apt install git

Fedora

sudo dnf install git

Arch Linux

sudo pacman -S git

インストール後、以下で確認します。

git --version

---

Android（Termux）

Termux を使用している場合は、以下を実行します。

pkg update
pkg install git

インストール後、以下で確認します。

git --version

---

iOS

iOS では BCSFE の動作環境が限られるため、Git のインストールは一般的ではありません。

もしターミナルアプリ（例：a-Shell）を使用する場合は、アプリの仕様に従って Git を導入してください。

---

Git のインストール後は、以下のコマンドで正常に導入されていることを確認できます。

git --version

バージョン番号（例: "git version 2.xx.x"）が表示されれば、BCSFE からロケールを追加できるようになります。
