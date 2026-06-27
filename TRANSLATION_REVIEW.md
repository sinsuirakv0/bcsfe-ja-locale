# BCSFE Japanese Locale Translation Review

BCSFE ????????????????????

- `EN` ??????????????
- `JA` ???????????
- ???? `.properties` ????????????????????????????
- ??????????????? `File` ? `Key` ???????????

## Summary

- Properties files: 27
- Translation keys: 787

| Category | File | ?? | Keys |
| --- | --- | --- | ---: |
| Core / ??UI | `files/core/main.properties` | ?????????????????Git???????? | 38 |
| Core / ??UI | `files/core/config.properties` | ????????? | 63 |
| Core / ??UI | `files/core/files.properties` | ????/?????? | 9 |
| Core / ??UI | `files/core/input.properties` | ?????????? | 24 |
| Core / ??UI | `files/core/locale.properties` | ??/?????? | 23 |
| Core / ??UI | `files/core/save.properties` | ???????/??/adb/root/Waydroid ?? | 89 |
| Core / ??UI | `files/core/server.properties` | ??????????????????????? | 38 |
| Core / ??UI | `files/core/theme.properties` | ????? | 15 |
| Core / ??UI | `files/core/updater.properties` | ?????? | 8 |
| Edit Features / ???? | `files/edits/items.properties` | ????????????????????? | 57 |
| Edit Features / ???? | `files/edits/bannable_items.properties` | BAN ????????????????? | 17 |
| Edit Features / ???? | `files/edits/cats.properties` | ??????????????????? | 115 |
| Edit Features / ???? | `files/edits/map.properties` | ???????????????????/???? | 127 |
| Edit Features / ???? | `files/edits/treasures.properties` | ???? | 24 |
| Edit Features / ???? | `files/edits/talent_orbs.properties` | ????? | 9 |
| Edit Features / ???? | `files/edits/gamototo.properties` | ????????????????? | 43 |
| Edit Features / ???? | `files/edits/gatya.properties` | ??????? | 8 |
| Edit Features / ???? | `files/edits/gold_pass.properties` | ?????? / ??????? | 6 |
| Edit Features / ???? | `files/edits/enemy.properties` | ??? | 17 |
| Edit Features / ???? | `files/edits/medals.properties` | ??????? | 8 |
| Edit Features / ???? | `files/edits/missions.properties` | ????? | 7 |
| Edit Features / ???? | `files/edits/playtime.properties` | ????? | 7 |
| Edit Features / ???? | `files/edits/scheme_items.properties` | ???????? | 6 |
| Edit Features / ???? | `files/edits/special_skills.properties` | ????? / ???? | 8 |
| Edit Features / ???? | `files/edits/user_rank.properties` | ????????? | 9 |
| Edit Features / ???? | `files/edits/fixes.properties` | ????? | 9 |
| Edit Features / ???? | `files/edits/gambling.properties` | ????/?????????? | 3 |

## ????

### Add Locale / ?????????

- File: `locale.json`

#### `short_name`

```text
"ja"
```

#### `name`

```text
"日本語"
```

#### `description`

```text
"Japanese localization draft for BCSFE"
```

#### `author`

```text
"健康おじ"
```

#### `version`

```text
"0.1.0"
```

### ??????????

- File: `files/metadata.json`

#### `name`

```text
"日本語 (Japanese)"
```

#### `authors`

```text
["健康おじ"]
```

## Core / ??UI

### ?????????????????Git????????

- File: `files/core/main.properties`
- Keys: 38

#### `downloading`

- Line: `37`
- EN:
```text
<@su>Downloading <@s>{file_name}</> from <@s>{pack_name}</> with version <@s>{version}</> and country code <@s>{country_code}</>
```
- JA:
```text
<@s>{pack_name}</> から <@s>{file_name}</> をダウンロードしています (バージョン <@s>{version}</>, 国コード <@s>{country_code}</>)
```

#### `failed_to_download_game_data`

- Line: `38`
- EN:
```text
<@e>Failed to download game data <@s>{file_name}</> from <@s>{pack_name}</> with version <@s>{version}</> with country code <@s>{country_code}</>. Url: <@s>{url}</s> Maybe check your internet connection.</>
```
- JA:
```text
<@e><@s>{pack_name}</> から <@s>{file_name}</> のゲームデータをダウンロードできませんでした (バージョン <@s>{version}</>, 国コード <@s>{country_code}</>)。URL: <@s>{url}</s> インターネット接続を確認してください。</>
```

#### `failed_to_get_game_versions`

- Line: `39`
- EN:
```text
<@e>Failed to get game versions. Maybe check your internet connection.</>
```
- JA:
```text
<@e>ゲームバージョンを取得できませんでした。インターネット接続を確認してください。</>
```

#### `no_device_error`

- Line: `40`
- EN:
```text
<@e>No connected devices found</>
```
- JA:
```text
<@e>接続中のデバイスが見つかりません</>
```

#### `no_package_name_error`

- Line: `41`
- EN:
```text
<@e>No battle cats packages found. Your device may not be rooted or you may need to try again and make sure you have entered the catbase at least once.</>
```
- JA:
```text
<@e>にゃんこ大戦争のパッケージが見つかりません。端末が root 化されていないか、もう一度試す前に一度ネコ基地に入る必要があるかもしれません。</>
```

#### `exit`

- Line: `42`
- EN:
```text
Exit
```
- JA:
```text
終了
```

#### `tkinter_not_found`

- Line: `43`
- EN:
```text
<@e>tkinter was not found. If you are not on mobile, please install it and try again.</>
```
- JA:
```text
<@e>tkinter が見つかりません。モバイル環境でない場合は、インストールしてから再試行してください。</>
```

#### `tkinter_not_found_enter_path_file`

- Line: `44`
- EN:
```text
Please enter the path/location of the {initialfile} file:
```
- JA:
```text
{initialfile} ファイルのパス/場所を入力してください:
```

#### `tkinter_not_found_enter_path_file_save`

- Line: `45`
- EN:
```text
Please enter the path/location to save the {initialfile} file:
```
- JA:
```text
{initialfile} ファイルの保存先パス/場所を入力してください:
```

#### `tkinter_not_found_enter_path_dir`

- Line: `46`
- EN:
```text
Please enter the path/location of the {initialdir} folder instead:
```
- JA:
```text
代わりに {initialdir} フォルダのパス/場所を入力してください:
```

#### `discord_url`

- Line: `47`
- EN:
```text
https://discord.gg/DvmMgvn5ZB
```
- JA:
```text
https://discord.gg/DvmMgvn5ZB
```

#### `welcome`

- Line: `49`
- EN:
```text

<@t>Welcome to the <@s>Battle Cats Save File Editor</>!
Made by <@s>fieryhenry</>

Codeberg: <@s>https://codeberg.org/fieryhenry/BCSFE-Python</>
Discord: <@s>{{discord_url}}</> - Please report any bugs to <@s>#bug-reports</> and suggestions to <@s>#suggestions</>
Donate: <@s>https://ko-fi.com/fieryhenry</>

Config File Location: <@s>{config_path}</>

{theme_text}

{locale_text}

<@q>Thanks To:
- <@s>Lethal's editor</> for giving me inspiration and helping me work out how to orignally patch the save data and edit cf/xp: <@s>https://www.reddit.com/r/BattleCatsCheats/comments/djehhn/editoren/</>
- <@s>Beeven</> and <@s>csehydrogen's</> code, which helped me figure out how to patch save data: https://github.com/beeven/battlecats and https://github.com/csehydrogen/BattleCatsHacker
- Anyone who has supported my work for giving me motivation to keep working on this and similar projects: <@s>https://ko-fi.com/fieryhenry</>
- Everyone in the discord for giving me saves, reporting bugs, suggesting new features, and for being an amazing community: <@s>{{discord_url}}</></>

<@w>If you paid for this program, you have been scammed. This program is free and open source.</>

<@w>Use this tool at your own risk. I am not responsible for any bans or damage caused to your save file.
Obviously, the save editor does try to prevent this from happening, but I cannot guarantee that your save is safe.
Though if your save does get corrupted please do still report it to the discord.
I recommend you to make backups of your save file before editing it.</>
```
- JA:
```text

<@t><@s>Battle Cats Save File Editor</> へようこそ!
作者: <@s>fieryhenry</>

Codeberg: <@s>https://codeberg.org/fieryhenry/BCSFE-Python</>
Discord: <@s>{{discord_url}}</> - バグ報告は <@s>#bug-reports</>、要望は <@s>#suggestions</> へ
寄付: <@s>https://ko-fi.com/fieryhenry</>

設定ファイルの場所: <@s>{config_path}</>

{theme_text}

{locale_text}

<@q>謝辞:
- <@s>Lethal's editor</>: セーブデータのパッチ方法や cat food/xp 編集方法を調べるうえで着想と助けを得ました: <@s>https://www.reddit.com/r/BattleCatsCheats/comments/djehhn/editoren/</>
- <@s>Beeven</> と <@s>csehydrogen</> のコード: セーブデータのパッチ方法を理解する助けになりました: https://github.com/beeven/battlecats and https://github.com/csehydrogen/BattleCatsHacker
- この開発を支援し、継続する動機をくれたすべての人: <@s>https://ko-fi.com/fieryhenry</>
- セーブ提供、バグ報告、新機能提案、そして素晴らしいコミュニティを作ってくれた Discord のみなさん: <@s>{{discord_url}}</></>

<@w>このプログラムにお金を払った場合、あなたはだまされています。このプログラムは無料かつオープンソースです。</>

<@w>このツールは自己責任で使用してください。BAN やセーブファイル破損などの損害について、作者は責任を負いません。
セーブエディタ側でも問題が起きないよう対策はしていますが、セーブが安全であることは保証できません。
もしセーブが破損した場合でも、Discord へ報告してください。
編集前にセーブファイルのバックアップを作成することをおすすめします。</>
```

#### `report_message`

- Line: `76`
- EN:
```text
Please report this to <@s>#bug-reports</> on the discord: <@s>{{discord_url}}</>
```
- JA:
```text
Discord の <@s>#bug-reports</> に報告してください: <@s>{{discord_url}}</>
```

#### `report_message_l`

- Line: `77`
- EN:
```text
please report this to <@s>#bug-reports</> on the discord: <@s>{{discord_url}}</>
```
- JA:
```text
discord の <@s>#bug-reports</> に報告してください: <@s>{{discord_url}}</>
```

#### `try_again_message`

- Line: `78`
- EN:
```text
Please try again. If error persists {{report_message_l}}</>
```
- JA:
```text
もう一度試してください。エラーが続く場合は {{report_message_l}}
```

#### `all`

- Line: `79`
- EN:
```text
All
```
- JA:
```text
すべて
```

#### `error`

- Line: `81`
- EN:
```text
<@e>An error has occurred (<@s>{error}</>, editor version: <@s>{version}</>) {{report_message_l}}\n{traceback}
```
- JA:
```text
<@e>エラーが発生しました (<@s>{error}</>, エディタバージョン: <@s>{version}</>) {{report_message_l}}\n{traceback}
```

#### `see_log`

- Line: `82`
- EN:
```text
<@e>Please see the log file for more details.</>
```
- JA:
```text
<@e>詳細はログファイルを確認してください。</>
```

#### `max`

- Line: `83`
- EN:
```text
max
```
- JA:
```text
最大
```

#### `none`

- Line: `84`
- EN:
```text
None
```
- JA:
```text
なし
```

#### `unknown`

- Line: `85`
- EN:
```text
Unknown
```
- JA:
```text
不明
```

#### `leave`

- Line: `87`
- EN:
```text
\n<@q>Thank you for using the Battle Cats Save File Editor!</>
```
- JA:
```text
\n<@q>Battle Cats Save File Editor をご利用いただきありがとうございました!</>
```

#### `checking_for_changes`

- Line: `88`
- EN:
```text
<@t>Checking for changes...</>
```
- JA:
```text
<@t>変更を確認しています...</>
```

#### `no_changes`

- Line: `89`
- EN:
```text
<@su>No changes found.</>
```
- JA:
```text
<@su>変更は見つかりませんでした。</>
```

#### `changes_found`

- Line: `90`
- EN:
```text
<@su>Changes found.</>
```
- JA:
```text
<@su>変更が見つかりました。</>
```

#### `y/n`

- Line: `92`
- EN:
```text
y/n
```
- JA:
```text
y/n
```

#### `yes`

- Line: `93`
- EN:
```text
yes
```
- JA:
```text
yes
```

#### `git_not_installed`

- Line: `95`
- EN:
```text
<@e>Git is not installed. Please install it, add it to PATH, and try again.</>
```
- JA:
```text
<@e>Git がインストールされていません。Git をインストールし、PATH に追加してから再試行してください。</>
```

#### `failed_to_get_repo`

- Line: `96`
- EN:
```text
<@e>Failed to get repo: "<@t>{url}</>". Maybe it doesn't exist, or you have no internet connection</>
```
- JA:
```text
<@e>リポジトリを取得できませんでした: "<@t>{url}</>"。存在しないか、インターネット接続がない可能性があります</>
```

#### `failed_to_run_git_cmd`

- Line: `97`
- EN:
```text
<@e>Failed to run git command: "<@t>{cmd}</>". Maybe check your internet connection</>
```
- JA:
```text
<@e>git コマンドを実行できませんでした: "<@t>{cmd}</>"。インターネット接続を確認してください</>
```

#### `cancel`

- Line: `98`
- EN:
```text
Cancel
```
- JA:
```text
キャンセル
```

#### `update_external`

- Line: `100`
- EN:
```text
Update External Content
```
- JA:
```text
外部コンテンツを更新
```

#### `updating_external_content`

- Line: `101`
- EN:
```text
<@q>Updating external content...</>
```
- JA:
```text
<@q>外部コンテンツを更新しています...</>
```

#### `downloading_map_names`

- Line: `103`
- EN:
```text
<@q>Getting map names... (code: <@t>{code}</>). This may take a while...</>
```
- JA:
```text
<@q>ステージ名を取得しています... (コード: <@t>{code}</>)。時間がかかる場合があります...</>
```

#### `select_device`

- Line: `105`
- EN:
```text
Select device:
```
- JA:
```text
デバイスを選択:
```

#### `continue_q`

- Line: `107`
- EN:
```text
Continue? ({{y/n}}):
```
- JA:
```text
続行しますか? ({{y/n}}):
```

#### `no_data_version`

- Line: `109`
- EN:
```text
<@e>The latest available game data version is not available. This is probably due to internet issues. Please try again.</>
```
- JA:
```text
<@e>利用可能な最新ゲームデータバージョンがありません。インターネット接続の問題の可能性があります。もう一度試してください。</>
```

#### `no_feature_with_name`

- Line: `111`
- EN:
```text
<@e>No feature found with name: <@s>{name}</></>
```
- JA:
```text
<@e>名前が <@s>{name}</> の機能は見つかりませんでした</>
```

### ?????????

- File: `files/core/config.properties`
- Keys: 63

#### `config`

- Line: `1`
- EN:
```text
Config
```
- JA:
```text
設定
```

#### `edit_config`

- Line: `2`
- EN:
```text
Edit config
```
- JA:
```text
設定を編集
```

#### `default_value`

- Line: `3`
- EN:
```text
(default value: <@q>{default_value}</>)
```
- JA:
```text
(初期値: <@q>{default_value}</>)
```

#### `current_value`

- Line: `4`
- EN:
```text
(current value: <@q>{current_value}</>)
```
- JA:
```text
(現在値: <@q>{current_value}</>)
```

#### `config_value_txt`

- Line: `5`
- EN:
```text
<@s>{{current_value}} {{default_value}}</>
```
- JA:
```text
<@s>{{current_value}} {{default_value}}</>
```

#### `config_dialog`

- Line: `7`
- EN:
```text
Select a config option to edit:
```
- JA:
```text
編集する設定項目を選択してください:
```

#### `update_to_beta_desc`

- Line: `9`
- EN:
```text
Check for updates to beta versions {{config_value_txt}}
```
- JA:
```text
ベータ版への更新も確認します {{config_value_txt}}
```

#### `update_to_beta`

- Line: `10`
- EN:
```text
Update to Beta Versions
```
- JA:
```text
ベータ版に更新する
```

#### `show_update_message_desc`

- Line: `12`
- EN:
```text
Show a message when a new version is available {{config_value_txt}}
```
- JA:
```text
新しいバージョンがあるときにメッセージを表示します {{config_value_txt}}
```

#### `show_update_message`

- Line: `13`
- EN:
```text
Show update message
```
- JA:
```text
更新メッセージを表示
```

#### `config_full`

- Line: `15`
- EN:
```text
<@t>{key_desc}</>
```
- JA:
```text
<@t>{key_desc}</>
```

#### `disable_maxes_desc`

- Line: `17`
- EN:
```text
Disable maximum values when editing {{config_value_txt}}
```
- JA:
```text
編集時の最大値制限を無効にします {{config_value_txt}}
```

#### `disable_maxes`

- Line: `18`
- EN:
```text
Disable maximum values
```
- JA:
```text
最大値制限を無効化
```

#### `max_backups_desc`

- Line: `20`
- EN:
```text
Maximum number of backups of save files to keep {{config_value_txt}}
```
- JA:
```text
保持するセーブファイルのバックアップ数の上限です {{config_value_txt}}
```

#### `max_backups`

- Line: `21`
- EN:
```text
Maximum save backups
```
- JA:
```text
セーブバックアップ数の上限
```

#### `available_themes`

- Line: `23`
- EN:
```text
Available themes:
```
- JA:
```text
利用可能なテーマ:
```

#### `theme_desc`

- Line: `24`
- EN:
```text
Theme to use {{config_value_txt}}
```
- JA:
```text
使用するテーマです {{config_value_txt}}
```

#### `theme`

- Line: `25`
- EN:
```text
Theme
```
- JA:
```text
テーマ
```

#### `show_missing_locale_keys`

- Line: `27`
- EN:
```text
Show missing locale keys
```
- JA:
```text
未翻訳のロケールキーを表示
```

#### `show_missing_locale_keys_desc`

- Line: `28`
- EN:
```text
Display all locale keys which are in the en locale, but not in the current locale. Useful for debugging purposes: {{config_value_txt}}
```
- JA:
```text
en ロケールにはあるが現在のロケールにはないキーをすべて表示します。デバッグ用です: {{config_value_txt}}
```

#### `reset_cat_data_desc`

- Line: `30`
- EN:
```text
Reset all cat data when removing a cat from the save file {{config_value_txt}}
```
- JA:
```text
セーブファイルからキャラを削除するとき、そのキャラの全データをリセットします {{config_value_txt}}
```

#### `reset_cat_data`

- Line: `31`
- EN:
```text
Reset cat data on cat removal
```
- JA:
```text
キャラ削除時にキャラデータをリセット
```

#### `filter_current_cats_desc`

- Line: `33`
- EN:
```text
When selecting cats to edit, filter out cats that are not in the save file {{config_value_txt}}
```
- JA:
```text
編集するキャラを選ぶとき、セーブファイル内に存在しないキャラを除外します {{config_value_txt}}
```

#### `filter_current_cats`

- Line: `34`
- EN:
```text
Filter current cats on cat selection 
```
- JA:
```text
キャラ選択時に所持キャラで絞り込み 
```

#### `set_cat_current_forms_desc`

- Line: `36`
- EN:
```text
When true forming cats, set the cat's current form to the newly unlocked form {{config_value_txt}}
```
- JA:
```text
キャラの形態を解放したとき、現在の形態を新しく解放した形態に設定します {{config_value_txt}}
```

#### `set_cat_current_forms`

- Line: `37`
- EN:
```text
Set cat current forms on form unlock
```
- JA:
```text
形態解放時に現在形態を設定
```

#### `strict_upgrade_desc`

- Line: `39`
- EN:
```text
When upgrading cats, check for things such as user rank and game progression so that you can only upgrade cats to a certain level {{config_value_txt}}
```
- JA:
```text
キャラを強化するとき、ユーザーランクや進行状況などを確認し、到達可能なレベルまでしか強化できないようにします {{config_value_txt}}
```

#### `strict_upgrade`

- Line: `40`
- EN:
```text
Strict upgrade checks
```
- JA:
```text
強化制限を厳密に確認
```

#### `separate_cat_edit_options_desc`

- Line: `42`
- EN:
```text
Separate the cat edit options into multiple features {{config_value_txt}}
```
- JA:
```text
キャラ編集オプションを複数の機能に分割します {{config_value_txt}}
```

#### `separate_cat_edit_options`

- Line: `43`
- EN:
```text
Separate cat edit options
```
- JA:
```text
キャラ編集オプションを分割
```

#### `strict_ban_prevention_desc`

- Line: `45`
- EN:
```text
When doing anything server related, create a new account to reduce the chance of getting banned {{config_value_txt}}
```
- JA:
```text
サーバー関連の操作を行うとき、BAN の可能性を下げるため新しいアカウントを作成します {{config_value_txt}}
```

#### `strict_ban_prevention`

- Line: `46`
- EN:
```text
Strict ban prevention
```
- JA:
```text
BAN 防止を厳密化
```

#### `max_request_timeout_desc`

- Line: `48`
- EN:
```text
Maximum time to wait for a request to complete (in seconds) {{config_value_txt}}
```
- JA:
```text
リクエスト完了まで待機する最大時間です (秒) {{config_value_txt}}
```

#### `max_request_timeout`

- Line: `49`
- EN:
```text
Maximum request timeout
```
- JA:
```text
リクエストタイムアウト上限
```

#### `game_data_repo_desc`

- Line: `51`
- EN:
```text
Repository to use for game data {{config_value_txt}}
```
- JA:
```text
ゲームデータに使用するリポジトリです {{config_value_txt}}
```

#### `game_data_repo`

- Line: `52`
- EN:
```text
Game data repository
```
- JA:
```text
ゲームデータリポジトリ
```

#### `game_data_repo_dialog`

- Line: `53`
- EN:
```text
Enter a game data repository to use:
```
- JA:
```text
使用するゲームデータリポジトリを入力してください:
```

#### `force_lang_game_data_desc`

- Line: `55`
- EN:
```text
Force the editor to use the game data for the current locale even if the save file is for a different version {{config_value_txt}}
```
- JA:
```text
セーブファイルが別バージョン向けでも、現在のロケール用ゲームデータを強制的に使用します {{config_value_txt}}
```

#### `force_lang_game_data`

- Line: `56`
- EN:
```text
Force use game data for current locale
```
- JA:
```text
現在のロケール用ゲームデータを強制使用
```

#### `clear_tutorial_on_load_desc`

- Line: `58`
- EN:
```text
Clear the tutorial when you load a save file into the editor {{config_value_txt}}
```
- JA:
```text
セーブファイルをエディタに読み込むとき、チュートリアルをクリア済みにします {{config_value_txt}}
```

#### `clear_tutorial_on_load`

- Line: `59`
- EN:
```text
Clear tutorial on save load
```
- JA:
```text
セーブ読込時にチュートリアルをクリア
```

#### `remove_ban_message_on_load_desc`

- Line: `61`
- EN:
```text
Remove the ban message when you load a save file into the editor {{config_value_txt}}
```
- JA:
```text
セーブファイルをエディタに読み込むとき、BAN メッセージを削除します {{config_value_txt}}
```

#### `remove_ban_message_on_load`

- Line: `62`
- EN:
```text
Remove ban message on save load
```
- JA:
```text
セーブ読込時に BAN メッセージを削除
```

#### `unlock_cat_on_edit_desc`

- Line: `64`
- EN:
```text
Unlock the cat when you edit its level, talents, form, etc. {{config_value_txt}}
```
- JA:
```text
レベル、才能、形態などを編集したとき、そのキャラを解放済みにします {{config_value_txt}}
```

#### `unlock_cat_on_edit`

- Line: `65`
- EN:
```text
Unlock cat on edit
```
- JA:
```text
編集時にキャラを解放
```

#### `use_file_dialog_desc`

- Line: `67`
- EN:
```text
Use the tkinter file dialog to open and save files instead of the file input {{config_value_txt}}
```
- JA:
```text
ファイル入力の代わりに tkinter のファイルダイアログでファイルを開く/保存します {{config_value_txt}}
```

#### `use_file_dialog`

- Line: `68`
- EN:
```text
Use file dialog
```
- JA:
```text
ファイルダイアログを使用
```

#### `adb_path_desc`

- Line: `70`
- EN:
```text
Path to the adb executable {{config_value_txt}}
```
- JA:
```text
adb 実行ファイルへのパスです {{config_value_txt}}
```

#### `adb_path`

- Line: `71`
- EN:
```text
ADB path
```
- JA:
```text
ADB パス
```

#### `use_pkexec_waydroid`

- Line: `73`
- EN:
```text
Use the pkexec binary to run waydroid commands
```
- JA:
```text
waydroid コマンド実行に pkexec を使用
```

#### `use_pkexec_waydroid_desc`

- Line: `74`
- EN:
```text
Running <@s>waydroid shell</> requires root access. Use <@s>pkexec</> to avoid running the whole editor as root {{config_value_txt}}
```
- JA:
```text
<@s>waydroid shell</> の実行には root 権限が必要です。エディタ全体を root で実行しないために <@s>pkexec</> を使用します {{config_value_txt}}
```

#### `use_waydroid`

- Line: `76`
- EN:
```text
Use waydroid shell rather than adb
```
- JA:
```text
adb の代わりに waydroid shell を使用
```

#### `use_waydroid_desc`

- Line: `77`
- EN:
```text
Waydroid doesn't support adb root, so use waydroid shell instead {{config_value_txt}}
```
- JA:
```text
Waydroid は adb root に対応していないため、代わりに waydroid shell を使用します {{config_value_txt}}
```

#### `ignore_parse_error_desc`

- Line: `79`
- EN:
```text
Ignore parsing errors and just skip parsing the rest of the save data. <@w>WARNING only really do this if your save file is corrupted, any parsing issues should be reported to the discord server</> {{config_value_txt}}
```
- JA:
```text
解析エラーを無視し、残りのセーブデータ解析をスキップします。<@w>警告: セーブファイルが破損している場合だけ使用してください。解析問題は Discord サーバーへ報告してください</> {{config_value_txt}}
```

#### `ignore_parse_error`

- Line: `80`
- EN:
```text
Ignore Save Parsing Errors
```
- JA:
```text
セーブ解析エラーを無視
```

#### `string_config_dialog`

- Line: `82`
- EN:
```text
Enter a new value for <@q>{val}</>:
```
- JA:
```text
<@q>{val}</> の新しい値を入力してください:
```

#### `enable_disable_dialog`

- Line: `85`
- EN:
```text
Do you want to <@q>enable</> or <@q>disable</> this feature?:
```
- JA:
```text
この機能を <@q>有効</> または <@q>無効</> にしますか?:
```

#### `enable`

- Line: `88`
- EN:
```text
Enable
```
- JA:
```text
有効
```

#### `disable`

- Line: `89`
- EN:
```text
Disable
```
- JA:
```text
無効
```

#### `enabled`

- Line: `91`
- EN:
```text
Enabled
```
- JA:
```text
有効
```

#### `disabled`

- Line: `92`
- EN:
```text
Disabled
```
- JA:
```text
無効
```

#### `config_success`

- Line: `94`
- EN:
```text
<@su>Successfully updated config</>
```
- JA:
```text
<@su>設定を更新しました</>
```

#### `yaml_create_error`

- Line: `96`
- EN:
```text
<@e>Failed to create yaml file at <@s>{path}<@s>, this is likely a permission issue on your end, maybe try running the editor as root/Administrator?
```
- JA:
```text
<@e><@s>{path}</> に yaml ファイルを作成できませんでした。権限の問題の可能性があります。root/管理者としてエディタを実行してみてください。
```

### ????/??????

- File: `files/core/files.properties`
- Keys: 9

#### `another_path`

- Line: `1`
- EN:
```text
Enter path manually
```
- JA:
```text
パスを手動入力
```

#### `select_files_dir`

- Line: `2`
- EN:
```text
Select files in directory:
```
- JA:
```text
ディレクトリ内のファイルを選択:
```

#### `enter_path`

- Line: `3`
- EN:
```text
Enter file path / location:
```
- JA:
```text
ファイルパス/場所を入力してください:
```

#### `enter_path_dir`

- Line: `4`
- EN:
```text
Enter folder path / location:
```
- JA:
```text
フォルダパス/場所を入力してください:
```

#### `enter_path_default`

- Line: `5`
- EN:
```text
Enter file path / location (default: <@t>{default}</>):
```
- JA:
```text
ファイルパス/場所を入力してください (既定: <@t>{default}</>):
```

#### `current_files_dir`

- Line: `6`
- EN:
```text
Current files in directory <@t>{dir}</>:
```
- JA:
```text
<@t>{dir}</> 内の現在のファイル:
```

#### `other_dir`

- Line: `7`
- EN:
```text
Enter other directory
```
- JA:
```text
別のディレクトリを入力
```

#### `no_files_dir`

- Line: `8`
- EN:
```text
<@e>No files in directory</>
```
- JA:
```text
<@e>ディレクトリ内にファイルがありません</>
```

#### `path_not_exists`

- Line: `9`
- EN:
```text
<@e>Path does not exist</>
```
- JA:
```text
<@e>パスが存在しません</>
```

### ??????????

- File: `files/core/input.properties`
- Keys: 24

#### `input_int`

- Line: `1`
- EN:
```text
Input a number between <@q>{min}</> and <@q>{max}</>:
```
- JA:
```text
<@q>{min}</> から <@q>{max}</> までの数値を入力してください:
```

#### `select_edit`

- Line: `2`
- EN:
```text
Select options for <@t>{group_name}</>:
```
- JA:
```text
<@t>{group_name}</> のオプションを選択してください:
```

#### `input_int_default`

- Line: `3`
- EN:
```text
Input a number between <@q>{min}</> and <@q>{max}</> (default <@q>{default}</>):
```
- JA:
```text
<@q>{min}</> から <@q>{max}</> までの数値を入力してください (既定 <@q>{default}</>):
```

#### `input_many`

- Line: `4`
- EN:
```text
Input numbers between <@q>{min}</> and <@q>{max}</> separated by spaces:
```
- JA:
```text
<@q>{min}</> から <@q>{max}</> までの数値をスペース区切りで入力してください:
```

#### `input_single`

- Line: `5`
- EN:
```text
Input a number between <@q>{min}</> and <@q>{max}</>:
```
- JA:
```text
<@q>{min}</> から <@q>{max}</> までの数値を入力してください:
```

#### `input`

- Line: `6`
- EN:
```text
Enter a value for <@t>{name}</> (current value: <@q>{value}</>) (max value: <@q>{max}</>):
```
- JA:
```text
<@t>{name}</> の値を入力してください (現在値: <@q>{value}</>) (最大値: <@q>{max}</>):
```

#### `input_min`

- Line: `7`
- EN:
```text
Enter a value for <@t>{name}</> (current value: <@q>{value}</>) (range: <@q>{min}</> - <@q>{max}</>):
```
- JA:
```text
<@t>{name}</> の値を入力してください (現在値: <@q>{value}</>) (範囲: <@q>{min}</> - <@q>{max}</>):
```

#### `input_non_max`

- Line: `8`
- EN:
```text
Enter a value for <@t>{name}</> (current value: <@q>{value}</>):
```
- JA:
```text
<@t>{name}</> の値を入力してください (現在値: <@q>{value}</>):
```

#### `input_all`

- Line: `9`
- EN:
```text
Enter a value for all <@t>{name}</> (max value: <@q>{max}</>):
```
- JA:
```text
すべての <@t>{name}</> の値を入力してください (最大値: <@q>{max}</>):
```

#### `value_changed`

- Line: `10`
- EN:
```text
<@su>Successfully changed <@s>{name}</> to <@s>{value}</>
```
- JA:
```text
<@su><@s>{name}</> を <@s>{value}</> に変更しました</>
```

#### `value_gave`

- Line: `11`
- EN:
```text
<@su>Successfully gave the <@s>{name}</>
```
- JA:
```text
<@su><@s>{name}</> を付与しました</>
```

#### `all_at_once`

- Line: `12`
- EN:
```text
Select all options at once
```
- JA:
```text
すべてのオプションを一括選択
```

#### `invalid_input`

- Line: `13`
- EN:
```text
<@e>Invalid input. Please try again.</>
```
- JA:
```text
<@e>入力が無効です。もう一度試してください。</>
```

#### `invalid_input_int`

- Line: `14`
- EN:
```text
<@e>Invalid input. Please enter a number between <@s>{min}</> and <@s>{max}</></>
```
- JA:
```text
<@e>入力が無効です。<@s>{min}</> から <@s>{max}</> までの数値を入力してください</>
```

#### `select_option`

- Line: `15`
- EN:
```text
Select option:
```
- JA:
```text
オプションを選択:
```

#### `finish`

- Line: `16`
- EN:
```text
Finish
```
- JA:
```text
完了
```

#### `features`

- Line: `17`
- EN:
```text
Features:
```
- JA:
```text
機能:
```

#### `go_back`

- Line: `18`
- EN:
```text
Go back
```
- JA:
```text
戻る
```

#### `yes_key`

- Line: `19`
- EN:
```text
y
```
- JA:
```text
y
```

#### `quit_key`

- Line: `20`
- EN:
```text
q
```
- JA:
```text
q
```

#### `range_input`

- Line: `21`
- EN:
```text
separated by spaces (e.g <@t>1 2 3 192</>), or enter a range (e.g. <@t>1-43</>) or enter <@t>all</>:
```
- JA:
```text
スペース区切り (例 <@t>1 2 3 192</>)、範囲指定 (例 <@t>1-43</>)、または <@t>all</> を入力してください:
```

#### `select_features`

- Line: `22`
- EN:
```text

To select a feature, enter
- a <@q>number</> corresponding to the number on the left
- <@t>text</> to search for a feature
You can press <@t>enter</> to view all features
Some features are <@t>categories</> and so when selected, will display all of its <@t>sub-features</>
Input:
```
- JA:
```text

機能を選択するには、次のいずれかを入力してください
- 左側の番号に対応する <@q>数字</>
- 機能を検索するための <@t>テキスト</>
<@t>Enter</> を押すとすべての機能を表示できます
一部の機能は <@t>カテゴリ</> です。選択すると、その <@t>サブ機能</> がすべて表示されます
入力:
```

#### `individual`

- Line: `30`
- EN:
```text
Individual
```
- JA:
```text
個別
```

#### `edit_all_at_once`

- Line: `31`
- EN:
```text
All at once
```
- JA:
```text
一括
```

### ??/??????

- File: `files/core/locale.properties`
- Keys: 23

#### `available_locales`

- Line: `1`
- EN:
```text
Available languages:
```
- JA:
```text
利用可能な言語:
```

#### `locale_desc`

- Line: `2`
- EN:
```text
Language to use {{config_value_txt}}
```
- JA:
```text
使用する言語です {{config_value_txt}}
```

#### `locale`

- Line: `3`
- EN:
```text
Language
```
- JA:
```text
言語
```

#### `locale_dialog`

- Line: `4`
- EN:
```text
Select a language:
```
- JA:
```text
言語を選択してください:
```

#### `add_locale`

- Line: `5`
- EN:
```text
Add Locale
```
- JA:
```text
ロケールを追加
```

#### `remove_locale`

- Line: `6`
- EN:
```text
Remove Locale
```
- JA:
```text
ロケールを削除
```

#### `locale_remove_dialog`

- Line: `7`
- EN:
```text
Select locales to remove:
```
- JA:
```text
削除するロケールを選択してください:
```

#### `enter_locale_git_repo`

- Line: `8`
- EN:
```text
Enter the git repository of the locale (e.g <@t>https://codeberg.org/fieryhenry/ExampleEditorLocale.git</>):
```
- JA:
```text
ロケールの git リポジトリを入力してください (例 <@t>https://codeberg.org/fieryhenry/ExampleEditorLocale.git</>):
```

#### `locale_already_exists`

- Line: `9`
- EN:
```text
<@e>A locale with name <@s>{locale_name}</> already exists.</>\nWould you like to overwrite it? ({{y/n}}):
```
- JA:
```text
<@e><@s>{locale_name}</> という名前のロケールはすでに存在します。</>\n上書きしますか? ({{y/n}}):
```

#### `locale_added`

- Line: `10`
- EN:
```text
<@su>Successfully added localization</>
```
- JA:
```text
<@su>ローカライズを追加しました</>
```

#### `checking_for_locale_updates`

- Line: `11`
- EN:
```text
Checking for updates to external localization <@t>{locale_name}</>...
```
- JA:
```text
外部ローカライズ <@t>{locale_name}</> の更新を確認しています...
```

#### `external_locale_updated`

- Line: `12`
- EN:
```text
<@su>Successfully updated external localization <@t>{locale_name}</> to version <@t>{version}<@t>.\n{{restart_to_see_changes}}</>
```
- JA:
```text
<@su>外部ローカライズ <@t>{locale_name}</> をバージョン <@t>{version}<@t> に更新しました。\n{{restart_to_see_changes}}</>
```

#### `external_locale_no_update`

- Line: `13`
- EN:
```text
<@su>No update needed for external localization <@t>{locale_name}</> latest version is <@t>{version}<@t></></>
```
- JA:
```text
<@su>外部ローカライズ <@t>{locale_name}</> は更新不要です。最新バージョンは <@t>{version}<@t> です</></>
```

#### `invalid_git_repo`

- Line: `14`
- EN:
```text
<@e>Invalid git repository</>
```
- JA:
```text
<@e>git リポジトリが無効です</>
```

#### `locale_cancelled`

- Line: `15`
- EN:
```text
<@e>Cancelled</>
```
- JA:
```text
<@e>キャンセルしました</>
```

#### `restart_to_see_changes`

- Line: `16`
- EN:
```text
You will need to restart the editor to see all of the changes
```
- JA:
```text
すべての変更を反映するにはエディタの再起動が必要です
```

#### `locale_changed`

- Line: `17`
- EN:
```text
<@su>Successfully changed locale to <@t>{locale_name}</>.\n{{restart_to_see_changes}}</>
```
- JA:
```text
<@su>ロケールを <@t>{locale_name}</> に変更しました。\n{{restart_to_see_changes}}</>
```

#### `locale_removed`

- Line: `18`
- EN:
```text
<@su>Successfully removed locale <@t>{locale_name}</>.\n{{restart_to_see_changes}}</>
```
- JA:
```text
<@su>ロケール <@t>{locale_name}</> を削除しました。\n{{restart_to_see_changes}}</>
```

#### `no_external_locales`

- Line: `19`
- EN:
```text
<@w>No external locales found</>
```
- JA:
```text
<@w>外部ロケールが見つかりません</>
```

#### `missing_locale_keys`

- Line: `21`
- EN:
```text
Missing Locale Keys:
```
- JA:
```text
不足しているロケールキー:
```

#### `extra_locale_keys`

- Line: `22`
- EN:
```text
Extra Locale Keys:
```
- JA:
```text
余分なロケールキー:
```

#### `locale_text`

- Line: `24`
- EN:
```text

Current Locale: <@s>{locale_name}</> (Version: <@s>{locale_version}</>)
Made by <@s>{locale_author}</>
Locale File Location: <@s>{locale_path}</>
```
- JA:
```text

現在のロケール: <@s>{locale_name}</> (バージョン: <@s>{locale_version}</>)
作成者: <@s>{locale_author}</>
ロケールファイルの場所: <@s>{locale_path}</>
```

#### `default_locale_text_authors`

- Line: `29`
- EN:
```text

Current Locale: <@s>{name}</>
Made by <@s>{authors}</>
Locale File Location: <@s>{path}</>
```
- JA:
```text

現在のロケール: <@s>{name}</>
作成者: <@s>{authors}</>
ロケールファイルの場所: <@s>{path}</>
```

### ???????/??/adb/root/Waydroid ??

- File: `files/core/save.properties`
- Keys: 89

#### `save_load_option`

- Line: `1`
- EN:
```text
Select an option to load the save file
```
- JA:
```text
セーブファイルの読み込み方法を選択してください:
```

#### `download_save`

- Line: `2`
- EN:
```text
Download save file using transfer and confirmation code
```
- JA:
```text
引継ぎコードと認証番号を使ってセーブファイルをダウンロード
```

#### `select_save_file`

- Line: `3`
- EN:
```text
Select save file from file
```
- JA:
```text
ファイルからセーブファイルを選択
```

#### `adb_pull_save`

- Line: `4`
- EN:
```text
Pull save file from device using adb
```
- JA:
```text
adb を使ってデバイスからセーブファイルを取得
```

#### `waydroid_pull_save`

- Line: `5`
- EN:
```text
Pull save from waydroid device
```
- JA:
```text
Waydroid デバイスからセーブを取得
```

#### `load_save_data_json`

- Line: `6`
- EN:
```text
Load save data from json
```
- JA:
```text
json からセーブデータを読み込み
```

#### `root_storage_pull_save`

- Line: `7`
- EN:
```text
Pull save file from root storage
```
- JA:
```text
root ストレージからセーブファイルを取得
```

#### `save_save_dialog`

- Line: `8`
- EN:
```text
Save save file
```
- JA:
```text
セーブファイルを保存
```

#### `save_downloaded`

- Line: `9`
- EN:
```text
<@su>Save file downloaded to <@s>{path}</>
```
- JA:
```text
<@su>セーブファイルを <@s>{path}</> にダウンロードしました</>
```

#### `save_json_dialog`

- Line: `10`
- EN:
```text
Save save data to json
```
- JA:
```text
セーブデータを json に保存
```

#### `load_from_documents`

- Line: `11`
- EN:
```text
Load save file from <@s>{path}</>
```
- JA:
```text
<@s>{path}</> からセーブファイルを読み込み
```

#### `save_file_not_found`

- Line: `12`
- EN:
```text
<@e>Save file not found</>
```
- JA:
```text
<@e>セーブファイルが見つかりません</>
```

#### `save_file_found`

- Line: `13`
- EN:
```text
<@su>Loading save from: <@t>{path}</></>
```
- JA:
```text
<@su>セーブを読み込んでいます: <@t>{path}</></>
```

#### `parse_save_error`

- Line: `15`
- EN:
```text
<@e>An error occurred while parsing your save file: {error}\n(editor version: <@s>{version}</>) (game version: <@s>{game_version}</>) (country code: <@s>{country_code}</>)\n{{report_message}}</>
```
- JA:
```text
<@e>セーブファイルの解析中にエラーが発生しました: {error}\n(エディタバージョン: <@s>{version}</>) (ゲームバージョン: <@s>{game_version}</>) (国コード: <@s>{country_code}</>)\n{{report_message}}</>
```

#### `load_json_fail`

- Line: `16`
- EN:
```text
<@e>Failed to load save data from json ({error})</>
```
- JA:
```text
<@e>json からセーブデータを読み込めませんでした ({error})</>
```

#### `parse_json_fail`

- Line: `17`
- EN:
```text
<@e>Failed to read json file, is your file actually in JSON format?</e>
```
- JA:
```text
<@e>json ファイルを読み取れませんでした。本当に JSON 形式のファイルですか?</e>
```

#### `editor_version_mismatch`

- Line: `18`
- EN:
```text
<@w>Editor version mismatch. Save file may not be compatible with this editor. Json Version: <@t>{json_version}</>, Editor Version: <@t>{editor_version}</></>
```
- JA:
```text
<@w>エディタバージョンが一致しません。このセーブファイルはこのエディタと互換性がない可能性があります。Json バージョン: <@t>{json_version}</>, エディタバージョン: <@t>{editor_version}</></>
```

#### `save_management`

- Line: `19`
- EN:
```text
Save Management
```
- JA:
```text
セーブ管理
```

#### `save_save`

- Line: `20`
- EN:
```text
Save save
```
- JA:
```text
セーブを保存
```

#### `save_save_file`

- Line: `21`
- EN:
```text
Save save to specific file
```
- JA:
```text
指定したファイルへセーブを保存
```

#### `save_save_documents`

- Line: `22`
- EN:
```text
Save save to {path}
```
- JA:
```text
{path} へセーブを保存
```

#### `save_upload`

- Line: `23`
- EN:
```text
Upload save file to server and get transfer and confirmation code
```
- JA:
```text
セーブファイルをサーバーへアップロードし、引き継ぎコードと認証番号を取得
```

#### `unban_account`

- Line: `24`
- EN:
```text
Unban Account / Fix Save Used Elsewhere Error
```
- JA:
```text
アカウントの BAN 解除 / 別端末使用中エラーを修正
```

#### `adb_push_rerun`

- Line: `26`
- EN:
```text
Use adb to push the save file to a device (Rerun the game after pushing)
```
- JA:
```text
adb を使ってセーブファイルをデバイスへ送信 (送信後にゲームを再起動)
```

#### `adb_push`

- Line: `27`
- EN:
```text
Use adb to push the save file to a device (Do not rerun the game after pushing)
```
- JA:
```text
adb を使ってセーブファイルをデバイスへ送信 (送信後にゲームを再起動しない)
```

#### `waydroid_push_rerun`

- Line: `28`
- EN:
```text
Push the save file to a waydroid device (Also rerun the game after pushing)
```
- JA:
```text
Waydroid デバイスへセーブファイルを送信 (送信後にゲームも再起動)
```

#### `waydroid_push`

- Line: `29`
- EN:
```text
Push the save file to a waydroid device (Do not rerun the game after pushing)
```
- JA:
```text
Waydroid デバイスへセーブファイルを送信 (送信後にゲームを再起動しない)
```

#### `adb_push_success`

- Line: `30`
- EN:
```text
<@su>Save file pushed to device</>
```
- JA:
```text
<@su>セーブファイルをデバイスへ送信しました</>
```

#### `adb_push_fail`

- Line: `31`
- EN:
```text
<@e>Failed to push save file to device</> ({error})
```
- JA:
```text
<@e>セーブファイルをデバイスへ送信できませんでした</> ({error})
```

#### `adb_rerun_success`

- Line: `32`
- EN:
```text
<@su>Successfully reran game</>
```
- JA:
```text
<@su>ゲームを再起動しました</>
```

#### `adb_rerun_fail`

- Line: `33`
- EN:
```text
<@e>Failed to rerun game</> ({error})
```
- JA:
```text
<@e>ゲームを再起動できませんでした</> ({error})
```

#### `waydroid_push_success`

- Line: `34`
- EN:
```text
<@su>Save file pushed to waydroid device</>
```
- JA:
```text
<@su>セーブファイルを Waydroid デバイスへ送信しました</>
```

#### `waydroid_push_fail`

- Line: `35`
- EN:
```text
<@e>Failed to push save file to waydroid device</> ({error})
```
- JA:
```text
<@e>セーブファイルを Waydroid デバイスへ送信できませんでした</> ({error})
```

#### `waydroid_rerun_success`

- Line: `36`
- EN:
```text
<@su>Successfully reran game on waydroid device</>
```
- JA:
```text
<@su>Waydroid デバイスでゲームを再起動しました</>
```

#### `waydroid_rerun_fail`

- Line: `37`
- EN:
```text
<@e>Failed to rerun game on waydroid device</> ({error})
```
- JA:
```text
<@e>Waydroid デバイスでゲームを再起動できませんでした</> ({error})
```

#### `export_save`

- Line: `39`
- EN:
```text
Export save file to json
```
- JA:
```text
セーブファイルを json にエクスポート
```

#### `save_success`

- Line: `40`
- EN:
```text
<@su>Save file saved to <@s>{path}</>
```
- JA:
```text
<@su>セーブファイルを <@s>{path}</> に保存しました</>
```

#### `export_success`

- Line: `41`
- EN:
```text
<@su>Save data exported to <@s>{path}</>
```
- JA:
```text
<@su>セーブデータを <@s>{path}</> にエクスポートしました</>
```

#### `init_save`

- Line: `42`
- EN:
```text
Reset save file
```
- JA:
```text
セーブファイルをリセット
```

#### `init_save_confirm`

- Line: `43`
- EN:
```text
Are you sure you want to reset your save file? ({{y/n}}):
```
- JA:
```text
本当にセーブファイルをリセットしますか? ({{y/n}}):
```

#### `init_save_success`

- Line: `44`
- EN:
```text
<@su>Succesfully reset save file</>
```
- JA:
```text
<@su>セーブファイルをリセットしました</>
```

#### `adb_pulling`

- Line: `46`
- EN:
```text
<@q>Pulling save file from device with package name <@s>{package_name}</>with adb ...</>
```
- JA:
```text
<@q>パッケージ名 <@s>{package_name}</> のセーブファイルを adb でデバイスから取得しています...</>
```

#### `adb_pull_fail`

- Line: `47`
- EN:
```text
<@e>Failed to pull save file from device with package name <@s>{package_name}</> ({error}) with adb
```
- JA:
```text
<@e>パッケージ名 <@s>{package_name}</> のセーブファイルを adb でデバイスから取得できませんでした ({error})
```

#### `waydroid_pulling`

- Line: `48`
- EN:
```text
<@q>Pulling save file from device with package name <@s>{package_name}</> with waydroid ...</>
```
- JA:
```text
<@q>パッケージ名 <@s>{package_name}</> のセーブファイルを waydroid でデバイスから取得しています...</>
```

#### `waydroid_pull_fail`

- Line: `49`
- EN:
```text
<@e>Failed to pull save file from device with package name <@s>{package_name}</> ({error}) with waydroid
```
- JA:
```text
<@e>パッケージ名 <@s>{package_name}</> のセーブファイルを waydroid でデバイスから取得できませんでした ({error})
```

#### `storage_pulling`

- Line: `51`
- EN:
```text
<@q>Pulling save file from root storage with package name <@s>{package_name}</>...</>
```
- JA:
```text
<@q>パッケージ名 <@s>{package_name}</> のセーブファイルを root ストレージから取得しています...</>
```

#### `storage_pull_fail`

- Line: `52`
- EN:
```text
<@e>Failed to pull save file from root storage with package name <@s>{package_name}</> ({error})
```
- JA:
```text
<@e>パッケージ名 <@s>{package_name}</> のセーブファイルを root ストレージから取得できませんでした ({error})
```

#### `not_rooted_error`

- Line: `54`
- EN:
```text
<@e>Device does not seem to be rooted, or the editor is not running as root</>
```
- JA:
```text
<@e>デバイスが root 化されていないか、エディタが root 権限で実行されていないようです</>
```

#### `upload_items`

- Line: `56`
- EN:
```text
Upload managed items to server
```
- JA:
```text
管理対象アイテムをサーバーへアップロード
```

#### `upload_items_success`

- Line: `57`
- EN:
```text
<@su>Successfully uploaded managed items</>
```
- JA:
```text
<@su>管理対象アイテムをアップロードしました</>
```

#### `upload_items_fail`

- Line: `58`
- EN:
```text
<@e>Failed to upload managed items</>
```
- JA:
```text
<@e>管理対象アイテムのアップロードに失敗しました</>
```

#### `load_save`

- Line: `60`
- EN:
```text
Load save file
```
- JA:
```text
セーブファイルを読み込み
```

#### `load_save_success`

- Line: `61`
- EN:
```text
<@su>Succesfully loaded save file</>
```
- JA:
```text
<@su>セーブファイルを読み込みました</>
```

#### `account`

- Line: `62`
- EN:
```text
Account
```
- JA:
```text
アカウント
```

#### `save_before_exit`

- Line: `64`
- EN:
```text
<@q>Save latest changes before exiting? (<@s>y</>/<@s>n</>):</>
```
- JA:
```text
<@q>終了前に最新の変更を保存しますか? (<@s>y</>/<@s>n</>):</>
```

#### `save_temp_success`

- Line: `65`
- EN:
```text
<@su>Succesfully managed to recover save file from temp file</>
```
- JA:
```text
<@su>一時ファイルからセーブファイルを復元しました</>
```

#### `save_temp_fail`

- Line: `66`
- EN:
```text
<@e>Failed to recover save file from temp file. Latest save changes are lost</> ({error})\n{traceback}
```
- JA:
```text
<@e>一時ファイルからセーブファイルを復元できませんでした。最新のセーブ変更は失われました</> ({error})\n{traceback}
```

#### `save_temp_not_found`

- Line: `67`
- EN:
```text
<@e>Failed to recover save file from temp file. Latest save changes are lost</> (Temp file not found)
```
- JA:
```text
<@e>一時ファイルからセーブファイルを復元できませんでした。最新のセーブ変更は失われました</> (一時ファイルが見つかりません)
```

#### `cant_detect_cc`

- Line: `69`
- EN:
```text
<@w>Failed to detect country code from save file. \nPlease enter your country code manually</>
```
- JA:
```text
<@w>セーブファイルから国コードを検出できませんでした。\n国コードを手動で入力してください</>
```

#### `failed_to_load_save_gv`

- Line: `70`
- EN:
```text
Save file loaded but certain values were not as expected. Error thrown to prevent save corruption
```
- JA:
```text
セーブファイルは読み込まれましたが、一部の値が想定と異なっていました。セーブ破損を防ぐためエラーにしました
```

#### `failed_to_load_save`

- Line: `71`
- EN:
```text
Failed to load save file
```
- JA:
```text
セーブファイルを読み込めませんでした
```

#### `failed_to_save_save`

- Line: `72`
- EN:
```text
Failed to save save file
```
- JA:
```text
セーブファイルを保存できませんでした
```

#### `game_version_dialog`

- Line: `74`
- EN:
```text
Enter game version (e.g <@t>12.2.1</>):
```
- JA:
```text
ゲームバージョンを入力してください (例 <@t>12.2.1</>):
```

#### `invalid_game_version`

- Line: `75`
- EN:
```text
<@e>Invalid game version</>
```
- JA:
```text
<@e>ゲームバージョンが無効です</>
```

#### `country_code_set`

- Line: `76`
- EN:
```text
<@su>Succesfully set country code to <@s>{cc}</>
```
- JA:
```text
<@su>国コードを <@s>{cc}</> に設定しました</>
```

#### `game_version_set`

- Line: `77`
- EN:
```text
<@su>Succesfully set game version to <@s>{version}</>
```
- JA:
```text
<@su>ゲームバージョンを <@s>{version}</> に設定しました</>
```

#### `convert_region`

- Line: `79`
- EN:
```text
Convert country code (e.g en -\> jp)
```
- JA:
```text
国コードを変換 (例 en -\> jp)
```

#### `convert_version`

- Line: `80`
- EN:
```text
Convert game version (e.g 12.2.1 -\> 12.2.0)
```
- JA:
```text
ゲームバージョンを変換 (例 12.2.1 -\> 12.2.0)
```

#### `cc_warning`

- Line: `82`
- EN:
```text
<@w>Warning: This may cause issues with your save file. Bugs and crashes are expected! If reporting a bug, please ensure to mention you have used this feature. You should enter the cat base / upgrade menu after running this feature so the game makes the necessary changes to your save file.</>\nCurrent country code: <@t>{current}</>
```
- JA:
```text
<@w>警告: セーブファイルに問題が起きる可能性があります。バグやクラッシュが発生することがあります。バグ報告時は、この機能を使用したことを必ず伝えてください。この機能の実行後、ゲーム側で必要な変更がセーブファイルへ反映されるよう、ネコ基地/パワーアップ画面に入ってください。</>\n現在の国コード: <@t>{current}</>
```

#### `gv_warning`

- Line: `83`
- EN:
```text
<@w>Warning: This may cause issues with your save file. Bugs and crashes are expected! If reporting a bug, plesae ensure to mention you have used this feature. You should enter the cat base / upgrade menu after running this feature so the game makes the necessary changes to your save file.</>\nCurrent game version: <@t>{current}</>
```
- JA:
```text
<@w>警告: セーブファイルに問題が起きる可能性があります。バグやクラッシュが発生することがあります。バグ報告時は、この機能を使用したことを必ず伝えてください。この機能の実行後、ゲーム側で必要な変更がセーブファイルへ反映されるよう、ネコ基地/パワーアップ画面に入ってください。</>\n現在のゲームバージョン: <@t>{current}</>
```

#### `create_new_save_success`

- Line: `85`
- EN:
```text
<@su>Succesfully created new save file</>
```
- JA:
```text
<@su>新しいセーブファイルを作成しました</>
```

#### `create_new_save`

- Line: `86`
- EN:
```text
Create new save file
```
- JA:
```text
新しいセーブファイルを作成
```

#### `create_new_save_warning`

- Line: `87`
- EN:
```text
<@w>Warning: Many editor features will not work with an auto-created save file, you need to load it in the game first, then reload it in the editor\nThis is likely to change in later editor versions.</>
```
- JA:
```text
<@w>警告: 自動作成されたセーブファイルでは、多くのエディタ機能が動作しません。まずゲームで読み込み、その後エディタで再読み込みする必要があります\nこの仕様は今後のエディタバージョンで変更される可能性があります。</>
```

#### `parse_ignored_error`

- Line: `89`
- EN:
```text
<@w>WARNING: <@e>{error}<>\n<@w>Ignoring due to the <@s>Ignore Parse Error</> config flag being set. This may cause issues!</> 
```
- JA:
```text
<@w>警告: <@e>{error}<>\n<@w><@s>Ignore Parse Error</> 設定が有効なため無視します。問題が起きる可能性があります!</> 
```

#### `select_package_name`

- Line: `91`
- EN:
```text
Select package name:
```
- JA:
```text
パッケージ名を選択:
```

#### `adb_not_installed`

- Line: `93`
- EN:
```text

<@e>adb has not been added to your PATH environment variable or the executable path is incorrect. Try editing the adb path in the config
Current Value: <@s>{path}</>
Error: <@s>{error}</></>
```
- JA:
```text

<@e>adb が PATH 環境変数に追加されていないか、実行ファイルのパスが正しくありません。設定から adb パスを編集してみてください
現在値: <@s>{path}</>
エラー: <@s>{error}</></>
```

#### `waydroid_not_installed`

- Line: `98`
- EN:
```text
<@e>Waydroid is not installed, or an error occured: {error}</>
```
- JA:
```text
<@e>Waydroid がインストールされていないか、エラーが発生しました: {error}</>
```

#### `root_push_not_android_error`

- Line: `100`
- EN:
```text
<@e>Root push is only available on android devices</>
```
- JA:
```text
<@e>root push は Android デバイスでのみ利用できます</>
```

#### `root_push_success`

- Line: `101`
- EN:
```text
<@su>Successfully wrote save to root storage</>
```
- JA:
```text
<@su>root ストレージへセーブを書き込みました</>
```

#### `root_push_fail`

- Line: `102`
- EN:
```text
<@e>Failed to write save to root storage. Error: <@s>{error}</></>
```
- JA:
```text
<@e>root ストレージへセーブを書き込めませんでした。エラー: <@s>{error}</></>
```

#### `root_rerun_success`

- Line: `104`
- EN:
```text
<@su>Successfully reran game</>
```
- JA:
```text
<@su>ゲームを再起動しました</>
```

#### `root_rerun_fail`

- Line: `105`
- EN:
```text
<@e>Failed to rerun game. Error: <@s>{error}</></>
```
- JA:
```text
<@e>ゲームを再起動できませんでした。エラー: <@s>{error}</></>
```

#### `root_push`

- Line: `107`
- EN:
```text
Use root to push save directly to the game
```
- JA:
```text
root を使ってセーブを直接ゲームへ送信
```

#### `root_push_rerun`

- Line: `108`
- EN:
```text
Use root to push save directly to the game (and rerun the game)
```
- JA:
```text
root を使ってセーブを直接ゲームへ送信 (その後ゲームを再起動)
```

#### `select_recent`

- Line: `110`
- EN:
```text
Select recent save:
```
- JA:
```text
最近のセーブを選択:
```

#### `recent_save`

- Line: `111`
- EN:
```text
<@s><@q>{inquiry_code}</> <@t>{cc}</>-<@t>{gv}</> @ <@t>{year}</>-<@t>{month}</>-<@t>{day}</> <@t>{hour}</>:<@t>{minute}</>:<@t>{second}</> - original path: <@q>{name}</></>
```
- JA:
```text
<@s><@q>{inquiry_code}</> <@t>{cc}</>-<@t>{gv}</> @ <@t>{year}</>-<@t>{month}</>-<@t>{day}</> <@t>{hour}</>:<@t>{minute}</>:<@t>{second}</> - 元のパス: <@q>{name}</></>
```

#### `load_recent_saves`

- Line: `113`
- EN:
```text
Load from recent saves and backups
```
- JA:
```text
最近のセーブとバックアップから読み込み
```

#### `no_recent_saves`

- Line: `114`
- EN:
```text
<@w>No recent saves</>
```
- JA:
```text
<@w>最近のセーブはありません</>
```

#### `current_save`

- Line: `115`
- EN:
```text
\nCurrent Save: <@t>{cc}</>-<@t>{gv}</> Inquiry: <@t>{inquiry_code}</>
```
- JA:
```text
\n現在のセーブ: <@t>{cc}</>-<@t>{gv}</> 問い合わせコード: <@t>{inquiry_code}</>
```

### ???????????????????????

- File: `files/core/server.properties`
- Keys: 38

#### `transfer_code`

- Line: `1`
- EN:
```text
Transfer Code
```
- JA:
```text
引継ぎコード
```

#### `enter_transfer_code`

- Line: `2`
- EN:
```text
Enter Transfer Code:
```
- JA:
```text
引継ぎコードを入力してください:
```

#### `confirmation_code`

- Line: `3`
- EN:
```text
Confirmation Code
```
- JA:
```text
認証番号
```

#### `enter_confirmation_code`

- Line: `4`
- EN:
```text
Enter Confirmation Code:
```
- JA:
```text
認証番号を入力してください:
```

#### `country_code`

- Line: `5`
- EN:
```text
Country Code
```
- JA:
```text
国コード
```

#### `country_code_select`

- Line: `6`
- EN:
```text
Select country code:
```
- JA:
```text
国コードを選択:
```

#### `invalid_codes_error`

- Line: `7`
- EN:
```text
<@e>Failed to download save file. Please check your transfer code and confirmation code and country code and try again.</>
```
- JA:
```text
<@e>セーブファイルのダウンロードに失敗しました。引継ぎコード、認証番号、国コードを確認してから再試行してください。</>
```

#### `display_response_debug_info_q`

- Line: `8`
- EN:
```text
Do you want to display the response debug info? ({{y/n}}):
```
- JA:
```text
レスポンスのデバッグ情報を表示しますか? ({{y/n}}):
```

#### `response_text_display`

- Line: `9`
- EN:
```text

URL: <@q>{url}</>
Request Headers: <@q>{request_headers}</>
Request Body: <@q>{request_body}</>

Response Headers: <@q>{response_headers}</>
Response Body: <@q>{response_body}</>
```
- JA:
```text

URL: <@q>{url}</>
リクエストヘッダー: <@q>{request_headers}</>
リクエスト本文: <@q>{request_body}</>

レスポンスヘッダー: <@q>{response_headers}</>
レスポンス本文: <@q>{response_body}</>
```

#### `downloading_save_file`

- Line: `17`
- EN:
```text
Downloading save file from server (transfer code: <@q>{transfer_code}</>, confirmation code: <@q>{confirmation_code}</>, country code: <@q>{country_code}</>)...
```
- JA:
```text
サーバーからセーブファイルをダウンロードしています (引継ぎコード: <@q>{transfer_code}</>, 認証番号: <@q>{confirmation_code}</>, 国コード: <@q>{country_code}</>)...
```

#### `upload_result`

- Line: `18`
- EN:
```text

<@su>
Transfer Code: <@s>{transfer_code}</>
Confirmation Code: <@s>{confirmation_code}</>
</>
```
- JA:
```text

<@su>
引継ぎコード: <@s>{transfer_code}</>
認証番号: <@s>{confirmation_code}</>
</>
```

#### `upload_fail`

- Line: `24`
- EN:
```text
<@e>Failed to upload save file. {{try_again_message}} {{see_log}}</>
```
- JA:
```text
<@e>セーブファイルのアップロードに失敗しました。{{try_again_message}} {{see_log}}</>
```

#### `unban_fail`

- Line: `25`
- EN:
```text
<@e>Failed to unban account. {{try_again_message}} {{see_log}}</>
```
- JA:
```text
<@e>アカウントの BAN 解除に失敗しました。{{try_again_message}} {{see_log}}</>
```

#### `unban_success`

- Line: `26`
- EN:
```text
<@su>Account unbanned successfully.</>
```
- JA:
```text
<@su>アカウントの BAN 解除に成功しました。</>
```

#### `upload_items_checker_confirm`

- Line: `27`
- EN:
```text
Some managed items have not yet been tracked for your current save file. Do you want to upload them now? ({{y/n}}):
```
- JA:
```text
現在のセーブファイルで、まだ追跡されていない管理対象アイテムがあります。今アップロードしますか? ({{y/n}}):
```

#### `strict_ban_prevention_enabled`

- Line: `28`
- EN:
```text
<@w>Strict Ban Prevention Enabled. A new account will be created before uploading save file / managed items.</>
```
- JA:
```text
<@w>厳密な BAN 防止が有効です。セーブファイル/管理対象アイテムをアップロードする前に新しいアカウントを作成します。</>
```

#### `create_new_account_success`

- Line: `29`
- EN:
```text
<@su>Account created successfully.</>
```
- JA:
```text
<@su>アカウントを作成しました。</>
```

#### `create_new_account_fail`

- Line: `30`
- EN:
```text
<@e>Failed to create account. {{try_again_message}} {{see_log}}</>
```
- JA:
```text
<@e>アカウントを作成できませんでした。{{try_again_message}} {{see_log}}</>
```

#### `uploading_save_file`

- Line: `32`
- EN:
```text
<@q>Uploading save file to server...</>
```
- JA:
```text
<@q>セーブファイルをサーバーへアップロードしています...</>
```

#### `getting_codes`

- Line: `33`
- EN:
```text
<@q>Getting transfer code and confirmation code...</>
```
- JA:
```text
<@q>引継ぎコードと認証番号を取得しています...</>
```

#### `getting_auth_token`

- Line: `34`
- EN:
```text
<@q>Getting account auth token...</>
```
- JA:
```text
<@q>アカウント認証トークンを取得しています...</>
```

#### `refreshing_password`

- Line: `35`
- EN:
```text
<@q>Refreshing account password...</>
```
- JA:
```text
<@q>アカウントパスワードを更新しています...</>
```

#### `getting_password`

- Line: `36`
- EN:
```text
<@q>Getting account password...</>
```
- JA:
```text
<@q>アカウントパスワードを取得しています...</>
```

#### `getting_save_key`

- Line: `37`
- EN:
```text
<@q>Getting account save key...</>
```
- JA:
```text
<@q>アカウントのセーブキーを取得しています...</>
```

#### `inquiry_code_warning`

- Line: `39`
- EN:
```text
<@w>WARNING: Editing your inquiry code can result in your account being unplayable. Use at your own risk.</>\n{{do_you_want_to_continue}}
```
- JA:
```text
<@w>警告: 問い合わせコードを編集すると、アカウントが使用不能になる可能性があります。自己責任で使用してください。</>\n{{do_you_want_to_continue}}
```

#### `password_refresh_token_warning`

- Line: `40`
- EN:
```text
<@w>WARNING: Editing your password refresh token can result in your account being unplayable. Use at your own risk.</>\n{{do_you_want_to_continue}}
```
- JA:
```text
<@w>警告: パスワード更新トークンを編集すると、アカウントが使用不能になる可能性があります。自己責任で使用してください。</>\n{{do_you_want_to_continue}}
```

#### `no_internet`

- Line: `42`
- EN:
```text
<@e>No internet connection. Please check your internet connection and try again.</>
```
- JA:
```text
<@e>インターネット接続がありません。接続を確認してから再試行してください。</>
```

#### `transfer_backup`

- Line: `44`
- EN:
```text
<@su>Saved backup transfer save file to <@t>{path}</></>
```
- JA:
```text
<@su>引継ぎ用セーブファイルのバックアップを <@t>{path}</> に保存しました</>
```

#### `transfer_backup_fail`

- Line: `45`
- EN:
```text
<@e>Failed to save transfer backup file to <@t>{path}</> due to {error}</>
```
- JA:
```text
<@e>{error} により、引継ぎ用バックアップファイルを <@t>{path}</> に保存できませんでした</>
```

#### `retry_auth_token`

- Line: `47`
- EN:
```text
<@e>Failed to get auth token, retrying...</>
```
- JA:
```text
<@e>認証トークンを取得できませんでした。再試行しています...</>
```

#### `downloading_compressed_data`

- Line: `49`
- EN:
```text
<@su>Downloading game data from <@s>{url}</></>
```
- JA:
```text
<@su><@s>{url}</> からゲームデータをダウンロードしています</>
```

#### `clear_game_data_q`

- Line: `50`
- EN:
```text
Do you want to clear all downloaded game data? ({{y/n}}):
```
- JA:
```text
ダウンロード済みのゲームデータをすべて削除しますか? ({{y/n}}):
```

#### `cleared_game_data`

- Line: `51`
- EN:
```text
<@su>Successfully cleared game data</>
```
- JA:
```text
<@su>ゲームデータを削除しました</>
```

#### `validating_game_repo`

- Line: `53`
- EN:
```text
Validating game data repo...
```
- JA:
```text
ゲームデータリポジトリを検証しています...
```

#### `invalid_response`

- Line: `54`
- EN:
```text
<@e>Invalid response code: <@s>{response_code}</>. Expected <@s>200</></>
```
- JA:
```text
<@e>レスポンスコードが無効です: <@s>{response_code}</>。期待値: <@s>200</></>
```

#### `no_internet_or_connection_error`

- Line: `55`
- EN:
```text
<@e>Failed to connect to game data repo</>
```
- JA:
```text
<@e>ゲームデータリポジトリへ接続できませんでした</>
```

#### `invalid_url`

- Line: `56`
- EN:
```text
<@e>Invalid URL</>
```
- JA:
```text
<@e>URL が無効です</>
```

#### `use_alternative_repo`

- Line: `58`
- EN:
```text
<@e>Failed to fetch game data repo, this may be an issue with your internet connection or the repo is blocked on your network.</> Would you like to swap to <@t>{repo}</t> as an alternative game data repo? ({{y/n}}):
```
- JA:
```text
<@e>ゲームデータリポジトリの取得に失敗しました。インターネット接続の問題か、ネットワーク上でリポジトリがブロックされている可能性があります。</> 代替のゲームデータリポジトリとして <@t>{repo}</t> に切り替えますか? ({{y/n}}):
```

### ?????

- File: `files/core/theme.properties`
- Keys: 15

#### `theme_text`

- Line: `1`
- EN:
```text

Current Theme: <@s>{theme_name}</> (Version <@s>{theme_version}</>)
Made by <@s>{theme_author}</>
Theme File Location: <@s>{theme_path}</>
```
- JA:
```text

現在のテーマ: <@s>{theme_name}</> (バージョン <@s>{theme_version}</>)
作成者: <@s>{theme_author}</>
テーマファイルの場所: <@s>{theme_path}</>
```

#### `default_theme_text`

- Line: `6`
- EN:
```text

Current Theme: <@s>Default</>
Theme File Location: <@s>{theme_path}</>
```
- JA:
```text

現在のテーマ: <@s>Default</>
テーマファイルの場所: <@s>{theme_path}</>
```

#### `checking_for_theme_updates`

- Line: `10`
- EN:
```text
Checking for updates to external theme <@t>{theme_name}</>...
```
- JA:
```text
外部テーマ <@t>{theme_name}</> の更新を確認しています...
```

#### `external_theme_updated`

- Line: `11`
- EN:
```text
<@su>Successfully updated external theme <@t>{theme_name}</> to version <@t>{version}<@t>.\n{{restart_to_see_changes}}</>
```
- JA:
```text
<@su>外部テーマ <@t>{theme_name}</> をバージョン <@t>{version}<@t> に更新しました。\n{{restart_to_see_changes}}</>
```

#### `external_theme_no_update`

- Line: `12`
- EN:
```text
<@su>No update needed for external theme <@t>{theme_name}</> latest version is <@t>{version}<@t></>
```
- JA:
```text
<@su>外部テーマ <@t>{theme_name}</> は更新不要です。最新バージョンは <@t>{version}<@t> です</>
```

#### `theme_changed`

- Line: `13`
- EN:
```text
<@su>Successfully changed theme to <@t>{theme_name}</>.\n{{restart_to_see_changes}}</>
```
- JA:
```text
<@su>テーマを <@t>{theme_name}</> に変更しました。\n{{restart_to_see_changes}}</>
```

#### `theme_removed`

- Line: `14`
- EN:
```text
<@su>Successfully removed theme <@t>{theme_name}</>.\n{{restart_to_see_changes}}</>
```
- JA:
```text
<@su>テーマ <@t>{theme_name}</> を削除しました。\n{{restart_to_see_changes}}</>
```

#### `no_external_themes`

- Line: `15`
- EN:
```text
<@w>No external themes found</>
```
- JA:
```text
<@w>外部テーマが見つかりません</>
```

#### `theme_dialog`

- Line: `18`
- EN:
```text
Select a theme:
```
- JA:
```text
テーマを選択してください:
```

#### `add_theme`

- Line: `19`
- EN:
```text
Add theme
```
- JA:
```text
テーマを追加
```

#### `remove_theme`

- Line: `20`
- EN:
```text
Remove theme
```
- JA:
```text
テーマを削除
```

#### `theme_remove_dialog`

- Line: `21`
- EN:
```text
Select themes to remove:
```
- JA:
```text
削除するテーマを選択してください:
```

#### `enter_theme_git_repo`

- Line: `22`
- EN:
```text
Enter the git repository of the theme (e.g <@t>https://codeberg.org/fieryhenry/ExampleEditorTheme.git</>):
```
- JA:
```text
テーマの git リポジトリを入力してください (例 <@t>https://codeberg.org/fieryhenry/ExampleEditorTheme.git</>):
```

#### `theme_already_exists`

- Line: `23`
- EN:
```text
<@e>A theme with name <@s>{theme_name}</> already exists.</>\nWould you like to overwrite it? ({{y/n}}):
```
- JA:
```text
<@e><@s>{theme_name}</> という名前のテーマはすでに存在します。</>\n上書きしますか? ({{y/n}}):
```

#### `theme_added`

- Line: `24`
- EN:
```text
<@su>Successfully added theme</>
```
- JA:
```text
<@su>テーマを追加しました</>
```

### ??????

- File: `files/core/updater.properties`
- Keys: 8

#### `local_version`

- Line: `1`
- EN:
```text
<@q>Local version: <@s>{local_version}</></>
```
- JA:
```text
<@q>ローカルバージョン: <@s>{local_version}</></>
```

#### `latest_version`

- Line: `2`
- EN:
```text
<@q>Latest version: <@s>{latest_version}</></>
```
- JA:
```text
<@q>最新バージョン: <@s>{latest_version}</></>
```

#### `update_check_fail`

- Line: `4`
- EN:
```text
<@e>Failed to check for updates. Maybe check your internet connection?</>
```
- JA:
```text
<@e>更新確認に失敗しました。インターネット接続を確認してください。</>
```

#### `update_available`

- Line: `6`
- EN:
```text

<@q>An update is available: <@s>{latest_version}</>
Would you like to update? <@t>({{y/n}})</>:
```
- JA:
```text

<@q>更新があります: <@s>{latest_version}</>
更新しますか? <@t>({{y/n}})</>:
```

#### `update_success`

- Line: `9`
- EN:
```text

<@t>Update successful
Please restart the application</>
```
- JA:
```text

<@t>更新が完了しました
アプリケーションを再起動してください</>
```

#### `update_fail`

- Line: `12`
- EN:
```text

<@e>Update failed
Please update manually</>
Command: <@s>pip install --upgrade bcsfe</>
```
- JA:
```text

<@e>更新に失敗しました
手動で更新してください</>
コマンド: <@s>pip install --upgrade bcsfe</>
```

#### `version_line`

- Line: `17`
- EN:
```text
{{local_version}} | {{latest_version}}
```
- JA:
```text
{{local_version}} | {{latest_version}}
```

#### `disable_update_message`

- Line: `19`
- EN:
```text
Would you like to disable update messages? <@t>({{y/n}}):</>
```
- JA:
```text
更新メッセージを無効にしますか? <@t>({{y/n}}):</>
```

## Edit Features / ????

### ?????????????????????

- File: `files/edits/items.properties`
- Keys: 57

#### `catamins`

- Line: `3`
- EN:
```text
Catamins
```
- JA:
```text
ネコビタン
```

#### `catfruit`

- Line: `4`
- EN:
```text
Catfruit
```
- JA:
```text
マタタビ
```

#### `base_materials`

- Line: `5`
- EN:
```text
Base Materials
```
- JA:
```text
城素材
```

#### `inquiry_code`

- Line: `6`
- EN:
```text
Inquiry Code
```
- JA:
```text
問い合わせコード
```

#### `rare_gatya_seed`

- Line: `7`
- EN:
```text
Rare Gacha Seed
```
- JA:
```text
レアガチャシード
```

#### `normal_gatya_seed`

- Line: `8`
- EN:
```text
Normal Gacha Seed
```
- JA:
```text
にゃんこガチャシード
```

#### `event_gatya_seed`

- Line: `9`
- EN:
```text
Event Gacha Seed
```
- JA:
```text
イベントガチャシード
```

#### `unlocked_slots`

- Line: `10`
- EN:
```text
Unlocked Slots|Equip Slots|Lineups
```
- JA:
```text
解放済みスロット|編成スロット|出撃スロット
```

#### `password_refresh_token`

- Line: `11`
- EN:
```text
Password Refresh Token
```
- JA:
```text
パスワード更新トークン
```

#### `challenge_score`

- Line: `12`
- EN:
```text
Challenge Score
```
- JA:
```text
チャレンジバトルスコア
```

#### `dojo_score`

- Line: `13`
- EN:
```text
Dojo Score
```
- JA:
```text
初心の間スコア
```

#### `items`

- Line: `14`
- EN:
```text
Items
```
- JA:
```text
アイテム
```

#### `user_rank_rewards`

- Line: `15`
- EN:
```text
Claim User Rank Rewards (Does not give rewards)
```
- JA:
```text
ユーザーランク報酬を受け取る (報酬自体は付与されません)
```

#### `catfood`

- Line: `17`
- EN:
```text
Cat Food
```
- JA:
```text
ネコカン
```

#### `xp`

- Line: `18`
- EN:
```text
XP
```
- JA:
```text
XP
```

#### `normal_tickets`

- Line: `19`
- EN:
```text
Normal Tickets|Basic Tickets|Silver Tickets
```
- JA:
```text
にゃんこチケット
```

#### `rare_tickets`

- Line: `20`
- EN:
```text
Rare Tickets|Gold Tickets
```
- JA:
```text
レアチケット
```

#### `platinum_tickets`

- Line: `21`
- EN:
```text
Platinum Tickets
```
- JA:
```text
プラチナチケット
```

#### `legend_tickets`

- Line: `22`
- EN:
```text
Legend Tickets
```
- JA:
```text
レジェンドチケット
```

#### `100_million_tickets`

- Line: `23`
- EN:
```text
100 Million Downloads Tickets|One Hundred Million Downloads Tickets
```
- JA:
```text
1億ダウンロード記念チケット
```

#### `100_million_warn`

- Line: `24`
- EN:
```text
<@w>Note: you will only be able to see and use the tickets if the 100 Million Downloads event is currently active</>
```
- JA:
```text
<@w>注意: 1億ダウンロードイベントが現在有効な場合のみ、このチケットを表示/使用できます</>
```

#### `platinum_shards`

- Line: `25`
- EN:
```text
Platinum Shards
```
- JA:
```text
プラチナのかけら
```

#### `np`

- Line: `26`
- EN:
```text
NP
```
- JA:
```text
NP
```

#### `leadership`

- Line: `27`
- EN:
```text
Leadership
```
- JA:
```text
リーダーシップ
```

#### `catseyes`

- Line: `28`
- EN:
```text
Catseyes
```
- JA:
```text
キャッツアイ
```

#### `battle_items`

- Line: `29`
- EN:
```text
Battle Items
```
- JA:
```text
バトルアイテム
```

#### `duration`

- Line: `30`
- EN:
```text
<@t>{days}</t> days, <@t>{hours}</t> hours, <@t>{minutes}</> minutes, <@t>{seconds}</> seconds
```
- JA:
```text
<@t>{days}</t> 日, <@t>{hours}</t> 時間, <@t>{minutes}</> 分, <@t>{seconds}</> 秒
```

#### `endless_item_item`

- Line: `31`
- EN:
```text
<@s>{item}</> : <@s>{int}</>
```
- JA:
```text
<@s>{item}</> : <@s>{int}</>
```

#### `endless_items_success`

- Line: `32`
- EN:
```text
<@su>Successfully edited endless items</>
```
- JA:
```text
<@su>アイテム使い放題を編集しました</>
```

#### `invalid_minute_count`

- Line: `33`
- EN:
```text
<@e>Invalid minute amount</>
```
- JA:
```text
<@e>分数が無効です</>
```

#### `enter_duration_minutes`

- Line: `34`
- EN:
```text
Enter the duration in minutes for the endless items to last for (if you enter <@t>infinity</> the items last forever):
```
- JA:
```text
アイテム使い放題の継続時間を分で入力してください (<@t>infinity</> と入力すると永久に継続します):
```

#### `infinity_duration`

- Line: `35`
- EN:
```text
<@t>infinity</>
```
- JA:
```text
<@t>infinity</>
```

#### `infinity`

- Line: `36`
- EN:
```text
Infinity
```
- JA:
```text
無限
```

#### `enter_duration_minutes_item`

- Line: `37`
- EN:
```text
Enter the duration in minutes for the endless <@t>{item}</> to last for (if you enter <@t>infinity</> the items last forever):
```
- JA:
```text
無期限 <@t>{item}</> の継続時間を分で入力してください (<@t>infinity</> と入力すると永久に継続します):
```

#### `battle_items_endless`

- Line: `38`
- EN:
```text
Endless Battle Items
```
- JA:
```text
アイテム使い放題(無期限化)
```

#### `talent_orbs`

- Line: `39`
- EN:
```text
Talent Orbs
```
- JA:
```text
本能玉
```

#### `scheme_items`

- Line: `40`
- EN:
```text
Scheme Items
```
- JA:
```text
外部報酬
```

#### `labyrinth_medals`

- Line: `41`
- EN:
```text
Labyrinth Medals
```
- JA:
```text
グランドアビス勲章
```

#### `restart_pack`

- Line: `42`
- EN:
```text
Restart Pack|Returner Mode
```
- JA:
```text
リスタートパック
```

#### `engineers`

- Line: `43`
- EN:
```text
Engineers
```
- JA:
```text
助手
```

#### `gamototo`

- Line: `44`
- EN:
```text
Gamatoto / Ototo
```
- JA:
```text
ガマトト / オトート
```

#### `special_skills`

- Line: `45`
- EN:
```text
Special Skills / Base Abilities
```
- JA:
```text
施設レベル
```

#### `treasure_chests`

- Line: `46`
- EN:
```text
Treasure Chests
```
- JA:
```text
本能玉宝箱
```

#### `unknown_treasure_chest_name`

- Line: `47`
- EN:
```text
Unknown Treasure Chest ({id})
```
- JA:
```text
不明な宝箱 ({id})
```

#### `rare_ticket_trade`

- Line: `49`
- EN:
```text
Rare Ticket Trade
```
- JA:
```text
レアチケット交換
```

#### `rare_ticket_trade_feature_name`

- Line: `50`
- EN:
```text
Rare Ticket Trade (Allows for unbannable rare tickets)
```
- JA:
```text
レアチケット交換 (BAN されにくいレアチケットを入手)
```

#### `other`

- Line: `52`
- EN:
```text
Other
```
- JA:
```text
その他
```

#### `gatya`

- Line: `53`
- EN:
```text
Gacha
```
- JA:
```text
ガチャ
```

#### `levels`

- Line: `54`
- EN:
```text
Levels / Story / Treasure
```
- JA:
```text
レベル / ストーリー / お宝
```

#### `cats_special_skills`

- Line: `55`
- EN:
```text
Cats / Special Skills
```
- JA:
```text
キャラ / 施設レベル
```

#### `gatya_item_unknown_name`

- Line: `57`
- EN:
```text
Unknown Item
```
- JA:
```text
不明なアイテム
```

#### `unknown_catamin_name`

- Line: `58`
- EN:
```text
Unknown Catamin <@t>{id}</>
```
- JA:
```text
不明なネコビタン <@t>{id}</>
```

#### `unknown_catseye_name`

- Line: `59`
- EN:
```text
Unknown Catseye <@t>{id}</>
```
- JA:
```text
不明なキャッツアイ <@t>{id}</>
```

#### `unknown_catfruit_name`

- Line: `60`
- EN:
```text
Unknown Catfruit <@t>{id}</>
```
- JA:
```text
不明なマタタビ <@t>{id}</>
```

#### `unknown_labyrinth_medal_name`

- Line: `61`
- EN:
```text
Unknown Labyrinth Medal <@t>{id}</>
```
- JA:
```text
グランドアビス勲章 <@t>{id}</>
```

#### `reset_golden_cat_cpus_success`

- Line: `63`
- EN:
```text
<@su>Successfully reset golden cat CPU uses</>
```
- JA:
```text
<@su>金ニャンピューターの使用回数をリセットしました</>
```

#### `reset_golden_cat_cpus`

- Line: `64`
- EN:
```text
Reset Golden Cat CPU Uses
```
- JA:
```text
ニャンピューター使用回数をリセット
```

### BAN ?????????????????

- File: `files/edits/bannable_items.properties`
- Keys: 17

#### `do_you_want_to_continue`

- Line: `1`
- EN:
```text
Do you want to continue? ({{y/n}}):
```
- JA:
```text
続行しますか? ({{y/n}}):
```

#### `catfood_warning`

- Line: `3`
- EN:
```text
<@w>WARNING: Editing in cat food can result in a ban. Use at your own risk.</>\n{{do_you_want_to_continue}}
```
- JA:
```text
<@w>警告: ネコカンを編集すると BAN される可能性があります。自己責任で使用してください。</>\n{{do_you_want_to_continue}}
```

#### `legend_ticket_warning`

- Line: `4`
- EN:
```text
<@w>WARNING: Editing in legend tickets can result in a ban. Use at your own risk.</>\n{{do_you_want_to_continue}}
```
- JA:
```text
<@w>警告: レジェンドチケットを編集すると BAN される可能性があります。自己責任で使用してください。</>\n{{do_you_want_to_continue}}
```

#### `rare_ticket_warning`

- Line: `5`
- EN:
```text

<@w>WARNING: Editing in rare tickets can result in a ban. Use at your own risk.</>
You can use the rare ticket trade feature to get rare tickets with a lower risk of ban.
```
- JA:
```text

<@w>警告: レアチケットを編集すると BAN される可能性があります。自己責任で使用してください。</>
BAN リスクを下げてレアチケットを入手するには、レアチケット交換機能を使用できます。
```

#### `platinum_ticket_warning`

- Line: `8`
- EN:
```text

<@w>WARNING: Editing in platinum tickets can result in a ban. Use at your own risk.</>
You can use the platinum shards feature to get platinum tickets with a lower risk of ban.
```
- JA:
```text

<@w>警告: プラチナチケットを編集すると BAN される可能性があります。自己責任で使用してください。</>
BAN リスクを下げてプラチナチケットを入手するには、プラチナのかけら機能を使用できます。
```

#### `select_an_option_to_continue`

- Line: `12`
- EN:
```text
Select an option to continue editing {feature_name}:
```
- JA:
```text
{feature_name} の編集を続けるにはオプションを選択してください:
```

#### `continue_editing`

- Line: `14`
- EN:
```text
Continue editing {feature_name}
```
- JA:
```text
{feature_name} の編集を続行
```

#### `go_to_safe_feature`

- Line: `15`
- EN:
```text
Go to the safer {safer_feature_name} feature
```
- JA:
```text
より安全な {safer_feature_name} 機能へ移動
```

#### `cancel_editing`

- Line: `16`
- EN:
```text
Cancel editing {feature_name}
```
- JA:
```text
{feature_name} の編集をキャンセル
```

#### `rare_ticket_trade_enter`

- Line: `18`
- EN:
```text
Enter the number of rare tickets you want to <@q>add</> (max value: <@q>{max}</>) (current amount: <@q>{current}</>):
```
- JA:
```text
<@q>追加</> したいレアチケット数を入力してください (最大値: <@q>{max}</>) (現在数: <@q>{current}</>):
```

#### `rare_ticket_trade_storage_full`

- Line: `19`
- EN:
```text
<@e>ERROR: You don't have enough space in your cat storage, please free 1 space!</>
```
- JA:
```text
<@e>エラー: にゃんこ貯蔵庫に十分な空きがありません。1枠空けてください!</>
```

#### `rare_ticket_successfully_traded`

- Line: `20`
- EN:
```text

<@su>Successfully gave {rare_ticket_count} rare tickets.</>
You now need to enter the cat storage and press the <@q>Use all</> button and then press the <@q>Trade for Ticket</> button to get your tickets.
```
- JA:
```text

<@su>{rare_ticket_count} 枚のレアチケットを付与しました。</>
チケットを受け取るには、にゃんこ貯蔵庫に入り、<@q>すべて使う</> ボタンを押してから <@q>チケットに交換</> ボタンを押してください。
```

#### `rare_tickets_l`

- Line: `24`
- EN:
```text
rare tickets
```
- JA:
```text
レアチケット
```

#### `rare_ticket_trade_l`

- Line: `25`
- EN:
```text
rare ticket trade
```
- JA:
```text
レアチケット交換
```

#### `rare_ticket_trade_maxed`

- Line: `27`
- EN:
```text
<@e>ERROR: You already have the maximum amount of rare tickets!\nPlease use some before running this feature!</>
```
- JA:
```text
<@e>エラー: すでにレアチケットの最大所持数に達しています!\nこの機能を実行する前にいくつか使用してください!</>
```

#### `platinum_tickets_l`

- Line: `29`
- EN:
```text
platinum tickets
```
- JA:
```text
プラチナチケット
```

#### `platinum_shards_l`

- Line: `30`
- EN:
```text
platinum shards
```
- JA:
```text
プラチナのかけら
```

### ???????????????????

- File: `files/edits/cats.properties`
- Keys: 115

#### `total_selected_cats`

- Line: `1`
- EN:
```text
<@t>{total}</> cats currently selected
```
- JA:
```text
現在 <@t>{total}</> 体のキャラが選択されています
```

#### `selected_cat`

- Line: `2`
- EN:
```text
<@t>{name}</> (<@t>{id}</>) is selected
```
- JA:
```text
<@t>{name}</> (<@t>{id}</>) が選択されています
```

#### `cat`

- Line: `4`
- EN:
```text
<@t>{name}</> (<@t>{id}</>)
```
- JA:
```text
<@t>{name}</> (<@t>{id}</>)
```

#### `special_skill`

- Line: `5`
- EN:
```text
<@t>{name}</> (<@t>{id}</>)
```
- JA:
```text
<@t>{name}</> (<@t>{id}</>)
```

#### `item`

- Line: `6`
- EN:
```text
<@t>{name}</> (<@t>{id}</>)
```
- JA:
```text
<@t>{name}</> (<@t>{id}</>)
```

#### `cat_quantity`

- Line: `7`
- EN:
```text
Enter the number of {{cat}} you want to add (default <@t>1</t>):
```
- JA:
```text
追加したい {{cat}} の数を入力してください (既定 <@t>1</t>):
```

#### `skill_quantity`

- Line: `8`
- EN:
```text
Enter the number of <@t>{name}</> you want to add (default <@t>1</t>):
```
- JA:
```text
追加したい <@t>{name}</> の数を入力してください (既定 <@t>1</t>):
```

#### `unrecognised_storage_item`

- Line: `9`
- EN:
```text
<@e>Unrecognised storage item. Item category: <@s>{item_type}</>. Item id: <@s>{id}</> </>
```
- JA:
```text
<@e>認識できない貯蔵庫アイテムです。アイテムカテゴリ: <@s>{item_type}</>。アイテム ID: <@s>{id}</> </>
```

#### `current_storage_items`

- Line: `10`
- EN:
```text
Current storage items:
```
- JA:
```text
現在の貯蔵庫アイテム:
```

#### `storage_is_empty`

- Line: `11`
- EN:
```text
Storage is empty
```
- JA:
```text
貯蔵庫は空です
```

#### `available_storage`

- Line: `12`
- EN:
```text
Available storage space: <@t>{slots}</>
```
- JA:
```text
利用可能な貯蔵庫の空き: <@t>{slots}</>
```

#### `display_storage`

- Line: `13`
- EN:
```text
Display storage
```
- JA:
```text
貯蔵庫を表示
```

#### `clear_storage`

- Line: `14`
- EN:
```text
Clear storage
```
- JA:
```text
貯蔵庫を空にする
```

#### `add_cats`

- Line: `15`
- EN:
```text
Add cats
```
- JA:
```text
キャラを追加
```

#### `add_special_skills`

- Line: `16`
- EN:
```text
Add special skills / base upgrades
```
- JA:
```text
青玉を追加
```

#### `remove_items`

- Line: `17`
- EN:
```text
Remove cats / skills
```
- JA:
```text
キャラ / 青玉を削除
```

#### `too_many_cats_selected`

- Line: `18`
- EN:
```text
<@e>Too many cats selected. Maximum is <@s>{max}</>. Got <@s>{current}</></>
```
- JA:
```text
<@e>選択したキャラが多すぎます。最大は <@s>{max}</>、現在は <@s>{current}</> です</>
```

#### `too_many_skills_selected`

- Line: `19`
- EN:
```text
<@e>Too many skills selected. Maximum is <@s>{max}</>. Got <@s>{current}</></>
```
- JA:
```text
<@e>選択した青玉が多すぎます。最大は <@s>{max}</>、現在は <@s>{current}</> です</>
```

#### `need_x_more_space`

- Line: `20`
- EN:
```text
<@e>Not enough storage space. Need <@s>{needs}</> more slots</>
```
- JA:
```text
<@e>貯蔵庫の空きが足りません。あと <@s>{needs}</> 枠必要です</>
```

#### `added_cats`

- Line: `21`
- EN:
```text
Added cats:
```
- JA:
```text
追加したキャラ:
```

#### `added_special_skills`

- Line: `22`
- EN:
```text
Added special skills:
```
- JA:
```text
追加した青玉:
```

#### `select_special_skills`

- Line: `23`
- EN:
```text
Select special skills
```
- JA:
```text
青玉を選択
```

#### `removed_items`

- Line: `24`
- EN:
```text
Removed items:
```
- JA:
```text
削除したアイテム:
```

#### `cat_storage`

- Line: `25`
- EN:
```text
Cat Storage
```
- JA:
```text
にゃんこ貯蔵庫
```

#### `storage_success`

- Line: `26`
- EN:
```text
<@su>Successfully edited cat storage</>
```
- JA:
```text
<@su>にゃんこ貯蔵庫を編集しました</>
```

#### `select_gv`

- Line: `28`
- EN:
```text

Enter the game versions to filter by. Examples are:
- Get cats in versions <@t>11.5.0</> only: <@t>11.5.0</>,
- Get cats in versions <@t>12.4.0</> and <@t>13.0.0</> only <@t>12.4.0 13.0.0</>
- Get all cats between versions <@t>12.4.0</> and <@t>13.0.0</> inclusive: <@t>12.4.0-13.0.0</>
Do note that any cats which do not appear in the upgrade menu cannot be selected here since their game version is set to <@t>-1</>.
Input:
```
- JA:
```text

絞り込むゲームバージョンを入力してください。例:
- バージョン <@t>11.5.0</> のキャラだけ取得: <@t>11.5.0</>,
- バージョン <@t>12.4.0</> と <@t>13.0.0</> のキャラだけ取得: <@t>12.4.0 13.0.0</>
- バージョン <@t>12.4.0</> から <@t>13.0.0</> までのキャラをすべて取得: <@t>12.4.0-13.0.0</>
パワーアップメニューに表示されないキャラは、ゲームバージョンが <@t>-1</> に設定されているため、ここでは選択できません。
入力:
```

#### `possible_gvs`

- Line: `36`
- EN:
```text
Possible game versions:
```
- JA:
```text
指定可能なゲームバージョン:
```

#### `no_valid_gvs_entered`

- Line: `38`
- EN:
```text
<@w>No valid game versions entered</>
```
- JA:
```text
<@w>有効なゲームバージョンが入力されていません</>
```

#### `select_cats_rarity`

- Line: `40`
- EN:
```text
Select cats based on rarity
```
- JA:
```text
レアリティでキャラを選択
```

#### `select_cats_name`

- Line: `41`
- EN:
```text
Select cats based on name
```
- JA:
```text
名前でキャラを選択
```

#### `select_cats_obtainable`

- Line: `42`
- EN:
```text
Select all obtainable cats
```
- JA:
```text
入手可能なキャラをすべて選択
```

#### `select_cats_not_obtainable`

- Line: `43`
- EN:
```text
Select all unobtainable cats
```
- JA:
```text
入手不可のキャラをすべて選択
```

#### `select_cats_gatya_banner`

- Line: `44`
- EN:
```text
Select cats based on gacha banner
```
- JA:
```text
ガチャバナーでキャラを選択
```

#### `select_cats_game_version`

- Line: `45`
- EN:
```text
Select cats by game version
```
- JA:
```text
ゲームバージョンでキャラを選択
```

#### `select_cats_all`

- Line: `46`
- EN:
```text
Select all cats
```
- JA:
```text
すべてのキャラを選択
```

#### `select_cats`

- Line: `47`
- EN:
```text
Select cats:
```
- JA:
```text
キャラを選択:
```

#### `and_mode_q`

- Line: `48`
- EN:
```text
Do you want to filter down the current selection (<@t>1</>), add to it (<@t>2</>) or replace it (<@t>3</>)?:
```
- JA:
```text
現在の選択を絞り込みますか (<@t>1</>)、選択に追加しますか (<@t>2</>)、置き換えますか (<@t>3</>)?:
```

#### `select_rarity`

- Line: `49`
- EN:
```text
Select cat rarity:
```
- JA:
```text
キャラのレアリティを選択:
```

#### `enter_name`

- Line: `50`
- EN:
```text
Enter cat name:
```
- JA:
```text
キャラ名を入力してください:
```

#### `select_name`

- Line: `51`
- EN:
```text
Select cat name:
```
- JA:
```text
キャラ名を選択:
```

#### `select_gatya_banner`

- Line: `52`
- EN:
```text
Enter gacha banner ids {{range_input}}
```
- JA:
```text
ガチャバナー ID を入力してください {{range_input}}
```

#### `cats`

- Line: `53`
- EN:
```text
Cats
```
- JA:
```text
キャラ
```

#### `edit_cats`

- Line: `54`
- EN:
```text
Edit cats
```
- JA:
```text
キャラを編集
```

#### `enter_cat_ids`

- Line: `55`
- EN:
```text
You can find cat IDs here: <@t>https://battlecats.miraheze.org/wiki/Cat_Release_Order</>\nEnter cat ids {{range_input}}
```
- JA:
```text
キャラ ID はここで確認できます: <@t>https://battlecats.miraheze.org/wiki/Cat_Release_Order</>\nキャラ ID を入力してください {{range_input}}
```

#### `select_cats_id`

- Line: `56`
- EN:
```text
Select cats by id
```
- JA:
```text
ID でキャラを選択
```

#### `no_cats_found_name`

- Line: `57`
- EN:
```text
<@w>No cats found with name <@s>{name}</></>
```
- JA:
```text
<@w><@s>{name}</> という名前のキャラは見つかりませんでした</>
```

#### `select_cats_again`

- Line: `59`
- EN:
```text
Select additional cats
```
- JA:
```text
追加のキャラを選択
```

#### `unlock_cats`

- Line: `60`
- EN:
```text
Unlock Cats|Get Cats
```
- JA:
```text
キャラを解放|キャラを入手
```

#### `remove_cats`

- Line: `61`
- EN:
```text
Remove Cats
```
- JA:
```text
キャラを削除
```

#### `upgrade_cats`

- Line: `62`
- EN:
```text
Upgrade Cats
```
- JA:
```text
キャラを強化
```

#### `true_form_cats`

- Line: `63`
- EN:
```text
True Form Cats
```
- JA:
```text
キャラを第3形態にする
```

#### `remove_true_form_cats`

- Line: `64`
- EN:
```text
Remove Cat True Forms
```
- JA:
```text
キャラの第3形態を削除
```

#### `upgrade_talents_cats`

- Line: `65`
- EN:
```text
Upgrade Cat Talents
```
- JA:
```text
キャラの本能を強化
```

#### `remove_talents_cats`

- Line: `66`
- EN:
```text
Remove Cat Talents
```
- JA:
```text
キャラの本能を削除
```

#### `unlock_cat_guide`

- Line: `67`
- EN:
```text
Claim Cat Guide
```
- JA:
```text
にゃんこ図鑑を登録済みにする
```

#### `remove_cat_guide`

- Line: `68`
- EN:
```text
Unclaim Cat Guide
```
- JA:
```text
にゃんこ図鑑を未登録にする
```

#### `finish_edit_cats`

- Line: `69`
- EN:
```text
Finish editing cats
```
- JA:
```text
キャラ編集を終了
```

#### `select_edit_cats_option`

- Line: `70`
- EN:
```text
Select an option to edit cats:
```
- JA:
```text
キャラを編集するオプションを選択してください:
```

#### `upgrade_success`

- Line: `72`
- EN:
```text
<@su>Successfully upgraded cats</>
```
- JA:
```text
<@su>キャラを強化しました</>
```

#### `upgrade_cats_select_mod`

- Line: `73`
- EN:
```text
Select an option to upgrade cats:
```
- JA:
```text
キャラを強化するオプションを選択してください:
```

#### `upgrade_individual`

- Line: `74`
- EN:
```text
Input an upgrade for each selected cat
```
- JA:
```text
選択した各キャラの強化値を入力
```

#### `selected_cat_upgrades`

- Line: `75`
- EN:
```text
{{selected_cat}}: <@t>{base_level}<@s>+</>{plus_level}</>
```
- JA:
```text
{{selected_cat}}: <@t>{base_level}<@s>+</>{plus_level}</>
```

#### `selected_cat_upgraded`

- Line: `76`
- EN:
```text
<@t>{name}</> (<@t>{id}</>) has been upgraded to <@t>{base_level}<@s>+</>{plus_level}
```
- JA:
```text
<@t>{name}</> (<@t>{id}</>) を <@t>{base_level}<@s>+</>{plus_level}</> に強化しました
```

#### `upgrade_all`

- Line: `77`
- EN:
```text
Input an upgrade to apply to all selected cats
```
- JA:
```text
選択したすべてのキャラに適用する強化値を入力
```

#### `upgrade_input`

- Line: `78`
- EN:
```text

Enter an upgrade level. Examples:
<@t>10<@s>+</>20</> = Base level 10, plus level 20
<@t>10<@s>+</></> = Base level 10, keep current plus level
<@t><@s>+</>20</> = Keep current base level, plus level 20
<@t>10</> = Base level 10, plus level 0
<@t>5<@q>-</>10<@s>+</>20<@q>-</>30</> = Random base level between 5 and 10, random plus level between 20 and 30
<@t>5<@q>-</>10<@s>+</></> = Random base level between 5 and 10, keep current plus level
<@t><@s>+</>20<@q>-</>30</> = Keep current base level, random plus level between 20 and 30
<@t>{{max}}<@s>+</>{{max}}</> = Max base level, max plus level
<@t>{{quit_key}}</> = Quit
Input:
```
- JA:
```text

強化レベルを入力してください。例:
<@t>10<@s>+</>20</> = 基本レベル 10、プラス値 20
<@t>10<@s>+</></> = 基本レベル 10、現在のプラス値を維持
<@t><@s>+</>20</> = 現在の基本レベルを維持、プラス値 20
<@t>10</> = 基本レベル 10、プラス値 0
<@t>5<@q>-</>10<@s>+</>20<@q>-</>30</> = 基本レベルを 5 から 10 の間でランダム、プラス値を 20 から 30 の間でランダム
<@t>5<@q>-</>10<@s>+</></> = 基本レベルを 5 から 10 の間でランダム、現在のプラス値を維持
<@t><@s>+</>20<@q>-</>30</> = 現在の基本レベルを維持、プラス値を 20 から 30 の間でランダム
<@t>{{max}}<@s>+</>{{max}}</> = 基本レベル最大、プラス値最大
<@t>{{quit_key}}</> = 終了
入力:
```

#### `max_upgrade`

- Line: `91`
- EN:
```text
Max Upgrade Level: <@t>{max_base}<@s>+</>{max_plus}</>
```
- JA:
```text
強化レベル上限: <@t>{max_base}<@s>+</>{max_plus}</>
```

#### `invalid_upgrade_base`

- Line: `93`
- EN:
```text
<@e>Invalid base level: <@s>{base}</>
```
- JA:
```text
<@e>基本レベルが無効です: <@s>{base}</>
```

#### `invalid_upgrade_base_random`

- Line: `94`
- EN:
```text
<@e>Invalid base level range: <@s>{min}</>-<@s>{max}</>
```
- JA:
```text
<@e>基本レベル範囲が無効です: <@s>{min}</>-<@s>{max}</>
```

#### `invalid_upgrade_plus`

- Line: `95`
- EN:
```text
<@e>Invalid plus level: <@s>{plus}</>
```
- JA:
```text
<@e>プラス値が無効です: <@s>{plus}</>
```

#### `invalid_upgrade_plus_random`

- Line: `96`
- EN:
```text
<@e>Invalid plus level range: <@s>{min}</>-<@s>{max}</>
```
- JA:
```text
<@e>プラス値範囲が無効です: <@s>{min}</>-<@s>{max}</>
```

#### `remove_true_form_success`

- Line: `98`
- EN:
```text
<@su>Successfully removed true forms</>
```
- JA:
```text
<@su>第3形態を削除しました</>
```

#### `true_form_success`

- Line: `99`
- EN:
```text
<@su>Successfully true formed cats</>
```
- JA:
```text
<@su>キャラを第3形態にしました</>
```

#### `remove_success`

- Line: `101`
- EN:
```text
<@su>Successfully removed cats</>
```
- JA:
```text
<@su>キャラを削除しました</>
```

#### `unlock_success`

- Line: `102`
- EN:
```text
<@su>Successfully unlocked cats</>
```
- JA:
```text
<@su>キャラを解放しました</>
```

#### `unlock_cat_guide_success`

- Line: `104`
- EN:
```text
<@su>Successfully claimed cat guide entries</>
```
- JA:
```text
<@su>にゃんこ図鑑項目を登録済みにしました</>
```

#### `remove_cat_guide_success`

- Line: `105`
- EN:
```text
<@su>Successfully unclaimed cat guide entries</>
```
- JA:
```text
<@su>にゃんこ図鑑項目を未登録にしました</>
```

#### `select_cats_current`

- Line: `107`
- EN:
```text
Select currently unlocked cats
```
- JA:
```text
現在解放済みのキャラを選択
```

#### `select_cats_not_unlocked`

- Line: `108`
- EN:
```text
Select cats that are not unlocked
```
- JA:
```text
まだ解放されていないキャラを選択
```

#### `talents_version_warning`

- Line: `110`
- EN:
```text

<@w>Warning: The editor's game data does not match this save file's game version. Talents may not work as expected.
Save Version: <@s>{save_version}</>
Game Data Version: <@s>{data_version}</>
If the game data is outdated, it should get updated within the next few days.</>
```
- JA:
```text

<@w>警告: エディタのゲームデータが、このセーブファイルのゲームバージョンと一致していません。本能が想定どおり動作しない可能性があります。
セーブバージョン: <@s>{save_version}</>
ゲームデータバージョン: <@s>{data_version}</>
ゲームデータが古い場合は、数日以内に更新されるはずです。</>
```

#### `talents_success`

- Line: `116`
- EN:
```text
<@su>Successfully upgraded cat talents</>
```
- JA:
```text
<@su>キャラの本能を強化しました</>
```

#### `talents_remove_success`

- Line: `117`
- EN:
```text
<@su>Successfully removed cat talents</>
```
- JA:
```text
<@su>キャラの本能を削除しました</>
```

#### `talents_individual`

- Line: `118`
- EN:
```text
Edit talents for each selected cat
```
- JA:
```text
選択した各キャラの本能を編集
```

#### `talents_all`

- Line: `119`
- EN:
```text
Max out talents for all selected cats
```
- JA:
```text
選択したすべてのキャラの本能を最大化
```

#### `upgrade_talents_select_mod`

- Line: `120`
- EN:
```text
Select an option to edit cat talents:
```
- JA:
```text
キャラの本能を編集するオプションを選択してください:
```

#### `no_talent_data`

- Line: `121`
- EN:
```text
<@w>There is no talent data for this cat</>
```
- JA:
```text
<@w>このキャラの本能データはありません</>
```

#### `talents`

- Line: `122`
- EN:
```text
Talents
```
- JA:
```text
本能
```

#### `upgrade_talent_cats`

- Line: `123`
- EN:
```text
Upgrade Cat Talents
```
- JA:
```text
キャラの本能を強化
```

#### `force_true_form_cats`

- Line: `124`
- EN:
```text
Force True Form Cats
```
- JA:
```text
キャラの第3形態を強制設定
```

#### `force_true_form_cats_warning`

- Line: `125`
- EN:
```text

<@w>Warning: Only use this if you know the cat has a true form, otherwise it will lead to a glitched true form.
The main use of this option is when the editor's game data is outdated and new true forms have not been added yet.</>
```
- JA:
```text

<@w>警告: そのキャラに第3形態があると分かっている場合のみ使用してください。そうでない場合、壊れた第3形態になります。
主な用途は、エディタのゲームデータが古く、新しい第3形態がまだ追加されていない場合です。</>
```

#### `filter_current_q`

- Line: `129`
- EN:
```text
Do you want to only select from cats that you have currently unlocked (<@t>1</>) or all cats (<@t>2</>)?:
```
- JA:
```text
現在解放済みのキャラだけから選択しますか (<@t>1</>)、それとも全キャラから選択しますか (<@t>2</>)?:
```

#### `select_cats_currently_option`

- Line: `130`
- EN:
```text
Select from cats that you have currently unlocked (e.g when selecting cats for a specific rarity, only select cats of that rarity that you have currently unlocked)
```
- JA:
```text
現在解放済みのキャラから選択 (例: 特定レアリティのキャラを選ぶとき、現在解放済みのそのレアリティのキャラだけを選択)
```

#### `select_cats_all_option`

- Line: `131`
- EN:
```text
Select from all cats
```
- JA:
```text
すべてのキャラから選択
```

#### `unlock_remove_cats`

- Line: `133`
- EN:
```text
Unlock Cats / Remove Cats
```
- JA:
```text
キャラを解放 / キャラを削除
```

#### `true_form_remove_form_cats`

- Line: `134`
- EN:
```text
True Form Cats / Remove Cat True Forms
```
- JA:
```text
第3形態にする / 第3形態を削除
```

#### `upgrade_talents_remove_talents_cats`

- Line: `135`
- EN:
```text
Upgrade Talents / Remove Talents Cats
```
- JA:
```text
本能を強化 / 本能を削除
```

#### `unlock_remove_cat_guide`

- Line: `136`
- EN:
```text
Claim / Unclaim Cat Guide Entries
```
- JA:
```text
にゃんこ図鑑項目を登録 / 未登録
```

#### `unlock_remove_q`

- Line: `138`
- EN:
```text
Do you want to <@t>Unlock</> or <@t>Remove</> cats?:
```
- JA:
```text
キャラを <@t>解放</> しますか、それとも <@t>削除</> しますか?:
```

#### `true_form_remove_form_q`

- Line: `139`
- EN:
```text
Do you want to <@t>True Form</> cats or <@t>Remove Cat True Forms</>?:
```
- JA:
```text
キャラを <@t>第3形態</> にしますか、それとも <@t>第3形態を削除</> しますか?:
```

#### `upgrade_talents_remove_talents_q`

- Line: `140`
- EN:
```text
Do you want to <@t>Upgrade</> or <@t>Remove</> cat talents?:
```
- JA:
```text
キャラの本能を <@t>強化</> しますか、それとも <@t>削除</> しますか?:
```

#### `unlock_cat_guide_remove_guide_q`

- Line: `141`
- EN:
```text
Do you want to <@t>Claim</> or <@t>Unclaim</> cat guide entries?:
```
- JA:
```text
にゃんこ図鑑項目を <@t>登録</> しますか、それとも <@t>未登録</> にしますか?:
```

#### `fourth_form_remove_form_cats`

- Line: `143`
- EN:
```text
Ultra Form Cats / Remove Cat Ultra Forms (4th Forms)
```
- JA:
```text
第4形態を削除
```

#### `force_fourth_form_cats`

- Line: `144`
- EN:
```text
Force Ultra Form Cats (4th Forms)
```
- JA:
```text
キャラの第4形態を強制設定
```

#### `fourth_form_success`

- Line: `145`
- EN:
```text
<@su>Successfully ultra formed cats</>
```
- JA:
```text
<@su>キャラを第4形態にしました</>
```

#### `remove_fourth_form_success`

- Line: `146`
- EN:
```text
<@su>Successfully removed ultra forms</>
```
- JA:
```text
<@su>第4形態を削除しました</>
```

#### `fourth_form_cats`

- Line: `147`
- EN:
```text
Ultra Form Cats
```
- JA:
```text
キャラを第4形態にする
```

#### `remove_fourth_form_cats`

- Line: `148`
- EN:
```text
Remove Cat Ultra Forms
```
- JA:
```text
キャラの第4形態を削除
```

#### `fourth_form_remove_form_q`

- Line: `149`
- EN:
```text
Do you want to <@t>Ultra Form</> cats or <@t>Remove Cat Ultra Forms</>?:
```
- JA:
```text
キャラを <@t>第4形態</> にしますか、それとも <@t>第4形態を削除</> しますか?:
```

#### `force_fourth_form_cats_warning`

- Line: `150`
- EN:
```text

<@w>Warning: Only use this if you know the cat has an ultra form, otherwise it will lead to a glitched 4th form.
The main use of this option is when the editor's game data is outdated and new forms have not been added yet.</>
```
- JA:
```text

<@w>警告: そのキャラに第4形態があると分かっている場合のみ使用してください。そうでない場合、壊れた第4形態になります。
主な用途は、エディタのゲームデータが古く、新しい形態がまだ追加されていない場合です。</>
```

#### `gatya_info_progress`

- Line: `154`
- EN:
```text
Downloading gacha info (<@t>{current}</>/<@t>{total}</>)
```
- JA:
```text
ガチャ情報をダウンロードしています (<@t>{current}</>/<@t>{total}</>)
```

#### `unknown_banner`

- Line: `155`
- EN:
```text
Unknown banner
```
- JA:
```text
不明なバナー
```

#### `banner_txt`

- Line: `156`
- EN:
```text
{name} (<@s>{int}</>)
```
- JA:
```text
{name} (<@s>{int}</>)
```

#### `filter_down_q_gatya`

- Line: `157`
- EN:
```text
Do you want to remove duplicate and unknown banners from the list? ({{y/n}}):
```
- JA:
```text
一覧から重複バナーと不明なバナーを削除しますか? ({{y/n}}):
```

#### `select_cats_non_gatya`

- Line: `159`
- EN:
```text
Select Non-Gacha Cats
```
- JA:
```text
ガチャ以外のキャラを選択
```

#### `finished_cats_selection`

- Line: `160`
- EN:
```text
Have you finished selecting cats? ({{y/n}}):
```
- JA:
```text
キャラの選択を完了しましたか? ({{y/n}}):
```

#### `downloading_cat_names`

- Line: `162`
- EN:
```text
<@su>Downloading cat names from <@s>{url}</></>
```
- JA:
```text
<@su><@s>{url}</> からキャラ名をダウンロードしています</>
```

### ???????????????????/????

- File: `files/edits/map.properties`
- Keys: 127

#### `tutorial_already_cleared`

- Line: `1`
- EN:
```text
<@w>You have already cleared the tutorial</>
```
- JA:
```text
<@w>チュートリアルはすでにクリア済みです</>
```

#### `tutorial_cleared`

- Line: `2`
- EN:
```text
<@su>Succesfully cleared tutorial</>
```
- JA:
```text
<@su>チュートリアルをクリアしました</>
```

#### `clear_tutorial`

- Line: `3`
- EN:
```text
Clear Tutorial
```
- JA:
```text
チュートリアルをクリア
```

#### `clear_stages`

- Line: `5`
- EN:
```text
Clear Stages
```
- JA:
```text
ステージをクリア
```

#### `unclear_stages`

- Line: `6`
- EN:
```text
Unclear Stages
```
- JA:
```text
ステージを未クリアに戻す
```

#### `clear_unclear_q`

- Line: `7`
- EN:
```text
Do you want to <@t>clear</> or <@t>unclear</> stages?:
```
- JA:
```text
ステージを <@t>クリア</> しますか、それとも <@t>未クリアに戻す</> しますか?:
```

#### `add_enigma_stages`

- Line: `9`
- EN:
```text
Add Enigma Stages
```
- JA:
```text
地図ステージを追加
```

#### `clear_enigma_stages`

- Line: `10`
- EN:
```text
Clear Enigma Stages
```
- JA:
```text
地図ステージをクリア
```

#### `current_enigma_stages`

- Line: `11`
- EN:
```text
Current Enigma Stages:
```
- JA:
```text
現在の地図ステージ:
```

#### `enigma_stage`

- Line: `12`
- EN:
```text
Enigma Stage <@q>{name}</> (id: <@q>{id}</>) 
```
- JA:
```text
地図ステージ <@q>{name}</> (id: <@q>{id}</>) 
```

#### `unknown_enigma_name`

- Line: `13`
- EN:
```text
Unknown Enigma Name (id: <@q>{id}</>)
```
- JA:
```text
不明な地図ステージ名 (id: <@q>{id}</>)
```

#### `enigma_select`

- Line: `14`
- EN:
```text
Select Enigma Stages to Add
```
- JA:
```text
追加する地図ステージを選択
```

#### `enigma_success`

- Line: `15`
- EN:
```text
<@su>Succesfully added Enigma Stages</>
```
- JA:
```text
<@su>地図ステージを追加しました</>
```

#### `wipe_enigma`

- Line: `16`
- EN:
```text
Do you want to wipe your current enigma stages? ({{y/n}}):
```
- JA:
```text
現在の地図ステージを消去しますか? ({{y/n}}):
```

#### `aku_realm_unlocked`

- Line: `17`
- EN:
```text
<@su>Succesfully unlocked Aku Realm</>
```
- JA:
```text
<@su>魔界編を解放しました</>
```

#### `unlock_aku_realm`

- Line: `18`
- EN:
```text
Unlock Aku Realm
```
- JA:
```text
魔界編を解放
```

#### `select_story_chapters`

- Line: `20`
- EN:
```text
Select Story Chapters
```
- JA:
```text
ストーリーを選択
```

#### `chapter_progress_txt`

- Line: `21`
- EN:
```text
(e.g <@q>0</> = no stages cleared, <@q>1</> = first stage cleared, <@q>2</> = first and second stage cleared, ... <@q>{max}</> = all stages cleared)
```
- JA:
```text
(例 <@q>0</> = クリア済みステージなし, <@q>1</> = 最初のステージをクリア済み, <@q>2</> = 1番目と2番目のステージをクリア済み, ... <@q>{max}</> = 全ステージクリア済み)
```

#### `edit_chapter_progress_all`

- Line: `22`
- EN:
```text
Enter the progress to set each chapter to {{chapter_progress_txt}}:
```
- JA:
```text
各章に設定する進行度を入力してください {{chapter_progress_txt}}:
```

#### `edit_chapter_progress`

- Line: `23`
- EN:
```text
Enter the progress to set <@t>{chapter_name}</> to {{chapter_progress_txt}}:
```
- JA:
```text
<@t>{chapter_name}</> に設定する進行度を入力してください {{chapter_progress_txt}}:
```

#### `edit_stage_clear_count`

- Line: `24`
- EN:
```text
Enter the number of times to clear the stage:
```
- JA:
```text
ステージのクリア回数を入力してください:
```

#### `story_cleared`

- Line: `25`
- EN:
```text
<@su>Succesfully cleared story</>
```
- JA:
```text
<@su>ストーリーをクリアしました</>
```

#### `individual_chapters`

- Line: `26`
- EN:
```text
Individual Chapters
```
- JA:
```text
個別の章
```

#### `all_chapters`

- Line: `27`
- EN:
```text
All Chapters
```
- JA:
```text
すべての章
```

#### `individual_chapters_dialog`

- Line: `28`
- EN:
```text
Do you want to edit the clear progress of each chapter <@t>individually</>? or set <@t>all</> chapters to the same progress?:
```
- JA:
```text
各章のクリア進行度を <@t>個別</> に編集しますか? それとも <@t>すべて</> の章を同じ進行度にしますか?:
```

#### `individual_clear_counts`

- Line: `29`
- EN:
```text
Individual Clear Counts
```
- JA:
```text
個別のクリア回数
```

#### `all_clear_counts`

- Line: `30`
- EN:
```text
All Clear Counts
```
- JA:
```text
すべて同じクリア回数
```

#### `individual_clear_counts_dialog`

- Line: `31`
- EN:
```text
Do you want to edit the clear count of each stage <@t>individually</>? or set <@t>all</> stages to the same clear count?:
```
- JA:
```text
各ステージのクリア回数を <@t>個別</> に編集しますか? それとも <@t>すべて</> のステージを同じクリア回数にしますか?:
```

#### `clear_story`

- Line: `32`
- EN:
```text
Main Story Chapters|Clear Story
```
- JA:
```text
メインストーリー|ストーリーをクリア
```

#### `map_name_star`

- Line: `34`
- EN:
```text
{name} {star} Crown
```
- JA:
```text
{name} {star} 冠
```

#### `clear`

- Line: `36`
- EN:
```text
Clear
```
- JA:
```text
クリア
```

#### `unclear`

- Line: `37`
- EN:
```text
Unclear
```
- JA:
```text
未クリアに戻す
```

#### `outbreaks`

- Line: `39`
- EN:
```text
Outbreaks / Zombie Stages
```
- JA:
```text
ゾンビステージ
```

#### `clear_unclear_outbreaks`

- Line: `41`
- EN:
```text
Do you want to <@t>clear</> or <@t>unclear</> outbreaks?:
```
- JA:
```text
ゾンビステージを <@t>クリア</> しますか、それとも <@t>未クリアに戻す</> しますか?:
```

#### `clear_outbreaks_success`

- Line: `42`
- EN:
```text
<@su>Succesfully cleared outbreaks</>
```
- JA:
```text
<@su>ゾンビステージをクリアしました</>
```

#### `unclear_outbreaks_success`

- Line: `43`
- EN:
```text
<@su>Succesfully uncleared outbreaks</>
```
- JA:
```text
<@su>ゾンビステージを未クリアに戻しました</>
```

#### `no_valid_outbreaks`

- Line: `44`
- EN:
```text
<@e>Error: no valid outbreaks found</>
```
- JA:
```text
<@e>エラー: 有効なゾンビステージが見つかりません</>
```

#### `aku_chapters`

- Line: `46`
- EN:
```text
Aku Realm Chapters
```
- JA:
```text
魔界編の章
```

#### `aku_clear_success`

- Line: `47`
- EN:
```text
<@su>Succesfully cleared Aku Realm</>
```
- JA:
```text
<@su>魔界編をクリアしました</>
```

#### `aku_current_stage`

- Line: `48`
- EN:
```text
Aku Realm Stage <@q>{name}</> (id: <@q>{id}</>)
```
- JA:
```text
魔界編ステージ <@q>{name}</> (id: <@q>{id}</>)
```

#### `itf_timed_scores`

- Line: `50`
- EN:
```text
Into the Future Timed Scores
```
- JA:
```text
未来編タイムスコア
```

#### `itf_timed_scores_dialog`

- Line: `51`
- EN:
```text
Do you want to edit timed scores for <@t>whole chapters at once</> or <@t>individual stages</>?
```
- JA:
```text
タイムスコアを <@t>章全体で一括</> 編集しますか、それとも <@t>個別ステージ</> ごとに編集しますか?
```

#### `itf_timed_scores_edited`

- Line: `52`
- EN:
```text
<@su>Succesfully edited Into The Future timed scores</>
```
- JA:
```text
<@su>未来編のタイムスコアを編集しました</>
```

#### `itf_timed_score_dialog`

- Line: `53`
- EN:
```text
Enter the timed score:
```
- JA:
```text
タイムスコアを入力してください:
```

#### `current_stage`

- Line: `54`
- EN:
```text
{chapter_name} <@t>{stage_name}</>
```
- JA:
```text
{chapter_name} <@t>{stage_name}</>
```

#### `itf_timed_scores_individual_dialog`

- Line: `55`
- EN:
```text
Do you want to edit the timed score of each selected stage <@t>individually</>? or set <@t>all</> selected stages to the same timed score?:
```
- JA:
```text
選択した各ステージのタイムスコアを <@t>個別</> に編集しますか? それとも <@t>選択したすべて</> のステージを同じタイムスコアにしますか?:
```

#### `filibuster_stage_reclearing_allowed`

- Line: `57`
- EN:
```text
<@su>Filibuster stage has successfully been re-enabled.</>
```
- JA:
```text
<@su>フィリバスターステージを再挑戦可能にしました。</>
```

#### `filibuster_reclearing`

- Line: `58`
- EN:
```text
Re-enable Filibuster Stage
```
- JA:
```text
フィリバスターステージを再挑戦可能にする
```

#### `all_selected_stages`

- Line: `60`
- EN:
```text
All Selected Stages
```
- JA:
```text
選択したすべてのステージ
```

#### `unknown_map_name`

- Line: `62`
- EN:
```text
Unknown Map Name (id: <@q>{id}</>)
```
- JA:
```text
不明なマップ名 (id: <@q>{id}</>)
```

#### `map_name`

- Line: `63`
- EN:
```text
{name} <@s>(id: <@q>{id}</>)</>
```
- JA:
```text
{name} <@s>(id: <@q>{id}</>)</>
```

#### `edit_map_chapters`

- Line: `64`
- EN:
```text
Select Chapters
```
- JA:
```text
章を選択
```

#### `clear_whole_chapters`

- Line: `66`
- EN:
```text
Clear Whole Chapters
```
- JA:
```text
章全体をクリア
```

#### `unclear_whole_chapters`

- Line: `67`
- EN:
```text
Unclear Whole Chapters
```
- JA:
```text
章全体を未クリアに戻す
```

#### `clear_specific_stages`

- Line: `69`
- EN:
```text
Clear Specific Stages
```
- JA:
```text
特定ステージをクリア
```

#### `unclear_specific_stages`

- Line: `70`
- EN:
```text
Unclear Specific Stages
```
- JA:
```text
特定ステージを未クリアに戻す
```

#### `select_clear_type`

- Line: `72`
- EN:
```text
Do you want to <@t>clear whole chapters</> or <@t>clear specific stages</>?:
```
- JA:
```text
<@t>章全体をクリア</> しますか、それとも <@t>特定ステージをクリア</> しますか?:
```

#### `select_unclear_type`

- Line: `73`
- EN:
```text
Do you want to <@t>unclear whole chapters</> or <@t>unclear specific stages</>?:
```
- JA:
```text
<@t>章全体を未クリアに戻す</> しますか、それとも <@t>特定ステージを未クリアに戻す</> しますか?:
```

#### `custom_star_count_per_chapter_yn`

- Line: `75`
- EN:
```text
Do you want to set a custom star/crown count for each chapter? ({{y/n}}):
```
- JA:
```text
各章にカスタム星/冠数を設定しますか? ({{y/n}}):
```

#### `modify_clear_amounts`

- Line: `76`
- EN:
```text
Setting clear times to <@t>1</> for each selected stage. Do you want to change this? ({{y/n}}):
```
- JA:
```text
選択した各ステージのクリア回数を <@t>1</> に設定します。これを変更しますか? ({{y/n}}):
```

#### `clear_amount_chapter`

- Line: `77`
- EN:
```text
Set a different clear amount for each selected chapter
```
- JA:
```text
選択した各章に異なるクリア回数を設定
```

#### `clear_amount_all`

- Line: `78`
- EN:
```text
Set the same clear amount for all selected chapters
```
- JA:
```text
選択したすべての章に同じクリア回数を設定
```

#### `clear_amount_stages`

- Line: `79`
- EN:
```text
Set a different clear amount for each selected stage
```
- JA:
```text
選択した各ステージに異なるクリア回数を設定
```

#### `select_clear_amount_type`

- Line: `80`
- EN:
```text
Enter the clear amount setting mode you want to use:
```
- JA:
```text
使用するクリア回数設定モードを入力してください:
```

#### `clear_amount_enter`

- Line: `81`
- EN:
```text
Enter the clear amount:
```
- JA:
```text
クリア回数を入力してください:
```

#### `custom_star_count_per_chapter`

- Line: `82`
- EN:
```text
Enter star/crown count (max <@q>{max}</>):
```
- JA:
```text
星/冠数を入力してください (最大 <@q>{max}</>):
```

#### `custom_star_count_per_chapter_unclear`

- Line: `84`
- EN:
```text

Enter the star/crown to remove:
<@s><@t>1</> = unclear from whole map</>
<@s><@t>2</> = unclear from 2nd, 3rd and 4th crown/star map</>
<@s><@t>3</> = unclear from 3rd and 4th crown/star map</>
<@s><@t>4</> = unclear from 4th crown/star map</>
(max <@q>{max}</>):
```
- JA:
```text

削除する星/冠を入力してください:
<@s><@t>1</> = マップ全体から未クリアに戻す</>
<@s><@t>2</> = 2冠/星、3冠/星、4冠/星マップから未クリアに戻す</>
<@s><@t>3</> = 3冠/星、4冠/星マップから未クリアに戻す</>
<@s><@t>4</> = 4冠/星マップから未クリアに戻す</>
(最大 <@q>{max}</>):
```

#### `current_sol_chapter`

- Line: `92`
- EN:
```text
Chapter <@t>{name}</> (id: <@q>{id}</>)
```
- JA:
```text
章 <@t>{name}</> (id: <@q>{id}</>)
```

#### `current_sol_star`

- Line: `93`
- EN:
```text
Star/Crown: <@q>{star}</>
```
- JA:
```text
星/冠: <@q>{star}</>
```

#### `current_sol_stage`

- Line: `94`
- EN:
```text
Stage <@q>{name}</> (id: <@q>{id}</>)
```
- JA:
```text
ステージ <@q>{name}</> (id: <@q>{id}</>)
```

#### `map_chapters_edited`

- Line: `95`
- EN:
```text
<@su>Succesfully edited chapters</>
```
- JA:
```text
<@su>章を編集しました</>
```

#### `sol`

- Line: `96`
- EN:
```text
Stories of Legend
```
- JA:
```text
レジェンドストーリー
```

#### `event`

- Line: `97`
- EN:
```text
Normal Event Stages
```
- JA:
```text
通常イベントステージ
```

#### `collab`

- Line: `98`
- EN:
```text
Collaboration Event Stages
```
- JA:
```text
コラボイベントステージ
```

#### `select_map`

- Line: `99`
- EN:
```text
Select Map
```
- JA:
```text
マップを選択
```

#### `select_map_dialog`

- Line: `100`
- EN:
```text

Select the maps you want to edit
You can enter a range of numbers (e.g <@q>1-5</>), individual numbers (e.g <@q>1 3 5</>), or a combination of both (e.g <@q>1-3 5</>)
You can also enter the name / part of a name of the map (e.g <@t>{example}</>) to search / select it
You can also enter the word <@q>all</> to select all chapters
Input:
```
- JA:
```text

編集するマップを選択してください
数値範囲 (例 <@q>1-5</>)、個別の数値 (例 <@q>1 3 5</>)、またはその組み合わせ (例 <@q>1-3 5</>) を入力できます
マップ名または名前の一部 (例 <@t>{example}</>) を入力して検索/選択することもできます
<@q>all</> と入力するとすべての章を選択できます
入力:
```

#### `no_map_found`

- Line: `106`
- EN:
```text
<@e>No map found with name <@s>{name}</></>
```
- JA:
```text
<@e><@s>{name}</> という名前のマップは見つかりませんでした</>
```

#### `finished_selecting_maps`

- Line: `107`
- EN:
```text
Have you finished selecting maps? ({{y/n}}):
```
- JA:
```text
マップの選択を完了しましたか? ({{y/n}}):
```

#### `current_maps`

- Line: `108`
- EN:
```text
Current Maps:
```
- JA:
```text
現在のマップ:
```

#### `select_stage`

- Line: `110`
- EN:
```text
Select Stage
```
- JA:
```text
ステージを選択
```

#### `gauntlets`

- Line: `112`
- EN:
```text
Gauntlets
```
- JA:
```text
強襲ステージ
```

#### `collab_gauntlets`

- Line: `113`
- EN:
```text
Collaboration Gauntlets
```
- JA:
```text
コラボ強襲ステージ
```

#### `uncanny`

- Line: `114`
- EN:
```text
Uncanny Legends
```
- JA:
```text
真レジェンドストーリー
```

#### `catamin_stages`

- Line: `115`
- EN:
```text
Catamin Stages
```
- JA:
```text
ネコビタンステージ
```

#### `behemoth_culling`

- Line: `116`
- EN:
```text
Behemoth Culling
```
- JA:
```text
超獣討伐ステージ
```

#### `legend_quest`

- Line: `117`
- EN:
```text
Legend Quest
```
- JA:
```text
レジェンドクエスト
```

#### `towers`

- Line: `118`
- EN:
```text
Towers
```
- JA:
```text
にゃんこ塔
```

#### `zero_legends`

- Line: `119`
- EN:
```text
Zero Legends
```
- JA:
```text
ゼロレジェンド
```

#### `unclear_other_stages`

- Line: `121`
- EN:
```text
Do you want to overwrite your current progress in the chapter? ({{y/n}}) <@t>n</> = just change clear times for selected stages, <@t>y</> = unclear later stages in the chapter which were previously cleared:
```
- JA:
```text
章内の現在の進行状況を上書きしますか? ({{y/n}}) <@t>n</> = 選択したステージのクリア回数だけを変更, <@t>y</> = 以前クリア済みだった章内の後続ステージを未クリアに戻す:
```

#### `select_stage_progress`

- Line: `123`
- EN:
```text
Enter the stage to clear up to and including:
```
- JA:
```text
ここまで含めてクリアするステージを入力してください:
```

#### `zero_legends_warning`

- Line: `125`
- EN:
```text
<@w>Warning: If the version of the game you are using does not have a zero legends map, the game will crash if you try to edit it to be clear!</>
```
- JA:
```text
<@w>警告: 使用中のゲームバージョンにゼロレジェンドマップがない場合、クリア済みに編集するとゲームがクラッシュします!</>
```

#### `stages_select`

- Line: `127`
- EN:
```text
Enter numbers {{range_input}}
```
- JA:
```text
数値を入力してください {{range_input}}
```

#### `change_clear_amount_catamin`

- Line: `129`
- EN:
```text
Change Chapter Clear Amount
```
- JA:
```text
章のクリア回数を変更
```

#### `clear_unclear_stage_catamin`

- Line: `130`
- EN:
```text
Clear / Unclear Catamin Stages
```
- JA:
```text
ネコビタンステージをクリア / 未クリアに戻す
```

#### `catamin_stage_clear_q`

- Line: `131`
- EN:
```text
Do you want to <@t>Change the amount of times you've cleared a catamin chapter</>, or just <@t>clear or unclear the stages</>?:
```
- JA:
```text
<@t>ネコビタン章のクリア回数を変更</> しますか、それとも単に <@t>ステージをクリア/未クリアに戻す</> しますか?:
```

#### `select_map_from_names`

- Line: `133`
- EN:
```text
Select Map
```
- JA:
```text
マップを選択
```

#### `enter_clear_amount_catamin_map`

- Line: `135`
- EN:
```text
Enter clear times to set for chapter <@t>{name}</> (ID: <@t>{id}</t>) (<@t>0</> = haven't cleared this chapter, <@t>3</> or more means the chapter disappears):
```
- JA:
```text
章 <@t>{name}</> (ID: <@t>{id}</t>) に設定するクリア回数を入力してください (<@t>0</> = この章を未クリア, <@t>3</> 以上 = 章が消えます):
```

#### `enter_clear_amount_catamin`

- Line: `136`
- EN:
```text
Enter clear times to set for selected chapters (<@t>0</> = haven't cleared the chapter, <@t>3</> or more means the chapter disappears):
```
- JA:
```text
選択した章に設定するクリア回数を入力してください (<@t>0</> = 章を未クリア, <@t>3</> 以上 = 章が消えます):
```

#### `catamin_stage_success`

- Line: `138`
- EN:
```text
<@su>Successfully edited catamin stages</>
```
- JA:
```text
<@su>ネコビタンステージを編集しました</>
```

#### `catamin_clear_amounts_q`

- Line: `140`
- EN:
```text
Do you want to edit the clear times for each chapter <@t>individually</> or <@t>all at once</>?:
```
- JA:
```text
各章のクリア回数を <@t>個別</> に編集しますか、それとも <@t>一括</> で編集しますか?:
```

#### `dojo_catclaw_championships`

- Line: `142`
- EN:
```text
Clear Dojo Catclaw Championships
```
- JA:
```text
にゃんこ道検定をクリア
```

#### `finished`

- Line: `144`
- EN:
```text
Finished
```
- JA:
```text
完了
```

#### `edit_chapters_q`

- Line: `145`
- EN:
```text
What do you want to edit?:
```
- JA:
```text
何を編集しますか?:
```

#### `clear_whole_chapter`

- Line: `147`
- EN:
```text
Clear whole chapter
```
- JA:
```text
章全体をクリア
```

#### `clear_to_specific_stage`

- Line: `148`
- EN:
```text
Clear to a specific stage
```
- JA:
```text
特定ステージまでクリア
```

#### `clear_whole_q`

- Line: `149`
- EN:
```text
Do you want to <@t>clear the whole chapter at once</> or <@t>clear up to a specific stage within the chapter</>?:
```
- JA:
```text
<@t>章全体を一括でクリア</> しますか、それとも <@t>章内の特定ステージまでクリア</> しますか?:
```

#### `clear_all`

- Line: `151`
- EN:
```text
Clear all chapters
```
- JA:
```text
すべての章をクリア
```

#### `handle_individually`

- Line: `152`
- EN:
```text
Edit each chapter individually
```
- JA:
```text
各章を個別に編集
```

#### `clear_chapters_q`

- Line: `154`
- EN:
```text
Do you want to <@t>clear all selected chapters</> or <@t>edit the progress of each chapter individually</>?:
```
- JA:
```text
<@t>選択したすべての章をクリア</> しますか、それとも <@t>各章の進行度を個別に編集</> しますか?:
```

#### `max_stars`

- Line: `155`
- EN:
```text
Enter the maximum crown (max: <@t>{max}</>):
```
- JA:
```text
最大冠数を入力してください (最大: <@t>{max}</>):
```

#### `edit_map_all`

- Line: `157`
- EN:
```text
Same clear count for all chapters
```
- JA:
```text
すべての章に同じクリア回数
```

#### `edit_chapters_q_all`

- Line: `158`
- EN:
```text
Do you want to set the <@t>same clear count for all selected chapters</> or edit the clear count of <@t>each chapter individually</>?
```
- JA:
```text
<@t>選択したすべての章に同じクリア回数</> を設定しますか、それとも <@t>各章のクリア回数</> を個別に編集しますか?
```

#### `edit_whole_chapter`

- Line: `160`
- EN:
```text
Set the same clear count for the whole chapter
```
- JA:
```text
章全体に同じクリア回数を設定
```

#### `edit_specific_stages`

- Line: `161`
- EN:
```text
Edit the clear count of specific stages
```
- JA:
```text
特定ステージのクリア回数を編集
```

#### `edit_chapter_q`

- Line: `162`
- EN:
```text
Do you want to <@t>set the same clear count all stages in the chapter</> or <@t>edit the clear count for specific stages</>?:
```
- JA:
```text
<@t>章内のすべてのステージに同じクリア回数を設定</> しますか、それとも <@t>特定ステージのクリア回数を編集</> しますか?:
```

#### `each_stage_individually`

- Line: `164`
- EN:
```text
Set a different clear count for each selected stage
```
- JA:
```text
選択した各ステージに異なるクリア回数を設定
```

#### `stage_all_at_once`

- Line: `165`
- EN:
```text
Set the same clear count for all selected stages
```
- JA:
```text
選択したすべてのステージに同じクリア回数を設定
```

#### `set_clear_count_stage_q`

- Line: `166`
- EN:
```text
Do you want to <@t>set a different clear count for each selected stage</> or <@t>set the same clear count for all selected stages</>?:
```
- JA:
```text
<@t>選択した各ステージに異なるクリア回数を設定</> しますか、それとも <@t>選択したすべてのステージに同じクリア回数を設定</> しますか?:
```

#### `unknown_stage_name`

- Line: `168`
- EN:
```text
Unknown stage name (index: <@t>{index}</>)
```
- JA:
```text
不明なステージ名 (index: <@t>{index}</>)
```

#### `current_stage_map`

- Line: `169`
- EN:
```text
<@t>{name} <@s>(index: <@q>{index}</>)</></>
```
- JA:
```text
<@t>{name} <@s>(index: <@q>{index}</>)</></>
```

#### `edit_progress_clear`

- Line: `171`
- EN:
```text
Edit Map Progress
```
- JA:
```text
マップ進行度を編集
```

#### `edit_progress_unclear`

- Line: `172`
- EN:
```text
Edit Map Progress (Supports unclearing)
```
- JA:
```text
マップ進行度を編集 (未クリア化対応)
```

#### `edit_clear_counts`

- Line: `173`
- EN:
```text
Edit Stage Clear Counts
```
- JA:
```text
ステージクリア回数を編集
```

#### `keep_selecting`

- Line: `175`
- EN:
```text
Keep Selecting
```
- JA:
```text
選択を続ける
```

#### `remove_selection`

- Line: `176`
- EN:
```text
Remove Selection
```
- JA:
```text
選択を解除
```

#### `finish_selection`

- Line: `177`
- EN:
```text
Finish Selection
```
- JA:
```text
選択を終了
```

#### `map_selection_q`

- Line: `178`
- EN:
```text
What do you want to do?
```
- JA:
```text
何をしますか?:
```

### ????

- File: `files/edits/treasures.properties`
- Keys: 24

#### `whole_chapters`

- Line: `1`
- EN:
```text
Whole Chapters
```
- JA:
```text
章全体
```

#### `individual_stages`

- Line: `2`
- EN:
```text
Individual Stages
```
- JA:
```text
個別ステージ
```

#### `treasure_groups`

- Line: `3`
- EN:
```text
Treasure Groups / Sets
```
- JA:
```text
お宝グループ / セット
```

#### `treasure_dialog`

- Line: `4`
- EN:
```text
Do you want to edit treasures for <@t>whole chapters at once</>, <@t>individual stages</> or individual <@t>treasure groups</>?:
```
- JA:
```text
<@t>章全体を一括</>、<@t>個別ステージ</>、または <@t>お宝グループ</> のどれのお宝を編集しますか?:
```

#### `treasures_edited`

- Line: `5`
- EN:
```text
<@su>Succesfully edited treasures</>
```
- JA:
```text
<@su>お宝を編集しました</>
```

#### `per_chapter`

- Line: `6`
- EN:
```text
Per Chapter
```
- JA:
```text
章ごと
```

#### `all_selected_chapters`

- Line: `7`
- EN:
```text
All Selected Chapters
```
- JA:
```text
選択したすべての章
```

#### `edit_per_chapter`

- Line: `8`
- EN:
```text
Do you want to edit data for <@t>all selected chapters</> or <@t>each chapter individually</>?:
```
- JA:
```text
<@t>選択したすべての章</> のデータを編集しますか、それとも <@t>各章を個別</> に編集しますか?:
```

#### `no_treasure`

- Line: `9`
- EN:
```text
No Treasure
```
- JA:
```text
お宝なし
```

#### `custom_treasure_level`

- Line: `10`
- EN:
```text
Custom Treasure Level (<@w>Only edit if you know what you're doing!</>)
```
- JA:
```text
カスタムお宝レベル (<@w>何をしているか分かる場合のみ編集してください!</>)
```

#### `treasure_level_dialog`

- Line: `11`
- EN:
```text
Enter the treasure level you want to set:
```
- JA:
```text
設定したいお宝レベルを入力してください:
```

#### `custom_treasure_level_dialog`

- Line: `12`
- EN:
```text
Enter the custom treasure level you want to set:
```
- JA:
```text
設定したいカスタムお宝レベルを入力してください:
```

#### `select_stage_by_id`

- Line: `13`
- EN:
```text
Select Stages by IDs
```
- JA:
```text
ID でステージを選択
```

#### `select_stage_by_name`

- Line: `14`
- EN:
```text
Select Stages by Names
```
- JA:
```text
名前でステージを選択
```

#### `select_stage_dialog`

- Line: `15`
- EN:
```text
Do you want to select stages by <@t>IDs</> or <@t>Names</>?:
```
- JA:
```text
ステージを <@t>ID</> と <@t>名前</> のどちらで選択しますか?:
```

#### `select_stage_id`

- Line: `16`
- EN:
```text
Enter the stage IDs you want to select {{range_input}}
```
- JA:
```text
選択したいステージ ID を入力してください {{range_input}}
```

#### `select_stages_name`

- Line: `17`
- EN:
```text
Select stages:
```
- JA:
```text
ステージを選択:
```

#### `select_treasure_groups`

- Line: `18`
- EN:
```text
Select the treasure groups you want to edit:
```
- JA:
```text
編集するお宝グループを選択してください:
```

#### `story_treasures`

- Line: `19`
- EN:
```text
Story Treasures
```
- JA:
```text
ストーリーのお宝
```

#### `current_chapter`

- Line: `20`
- EN:
```text
Current Chapter: <@t>{chapter_name}</>
```
- JA:
```text
現在の章: <@t>{chapter_name}</>
```

#### `current_treasure_group`

- Line: `21`
- EN:
```text
Current Treasure Group: <@t>{treasure_group_name}</>
```
- JA:
```text
現在のお宝グループ: <@t>{treasure_group_name}</>
```

#### `group_individual`

- Line: `22`
- EN:
```text
Individual Groups
```
- JA:
```text
個別グループ
```

#### `group_all_at_once`

- Line: `23`
- EN:
```text
All Selected Groups
```
- JA:
```text
選択したすべてのグループ
```

#### `select_treasure_groups_individual`

- Line: `24`
- EN:
```text
Do you want to edit the treasure level for each <@t>treasure group</> individually or for <@t>all selected groups</> at once?:
```
- JA:
```text
各 <@t>お宝グループ</> のお宝レベルを個別に編集しますか、それとも <@t>選択したすべてのグループ</> を一括で編集しますか?:
```

### ?????

- File: `files/edits/talent_orbs.properties`
- Keys: 9

#### `total_current_orbs`

- Line: `1`
- EN:
```text
Total Current Orbs: <@q>{total_orbs}</>
```
- JA:
```text
現在の本能玉合計: <@q>{total_orbs}</>
```

#### `total_current_orb_types`

- Line: `2`
- EN:
```text
Total Current Orb Types: <@q>{total_types}</>
```
- JA:
```text
現在の本能玉タイプ数: <@q>{total_types}</>
```

#### `current_orbs`

- Line: `3`
- EN:
```text
Current Orbs:
```
- JA:
```text
現在の本能玉:
```

#### `orb_select`

- Line: `4`
- EN:
```text
Select talent orbs to edit:
```
- JA:
```text
編集する本能玉を選択:
```

#### `selected_orbs`

- Line: `5`
- EN:
```text
Selected talent Orbs:
```
- JA:
```text
選択中の本能玉:
```

#### `edit_orbs_individually`

- Line: `6`
- EN:
```text
Do you want to edit each orb individually (<@q>1</>) or all at once (<@q>2</>)?:
```
- JA:
```text
各本能玉を個別に編集しますか (<@q>1</>)、それとも一括で編集しますか (<@q>2</>)?:
```

#### `edit_orbs_all`

- Line: `7`
- EN:
```text
Input a value to edit all selected orbs to (max <@t>{max}</>):
```
- JA:
```text
選択したすべての本能玉を編集する値を入力してください (最大 <@t>{max}</>):
```

#### `failed_to_load_orbs`

- Line: `8`
- EN:
```text
Failed to load talent orbs
```
- JA:
```text
本能玉を読み込めませんでした
```

#### `edit_orbs_help`

- Line: `10`
- EN:
```text

Help:
Available grades: {all_grades_str}
Available attributes: {all_attributes_str}
Available effects: {all_effects_str}
<@w>Note: Not all grades and effects will be available for all attributes.</>
Example inputs:
    <c>aku</> - selects <c>all aku</> orbs
    <r>red</> <b>s</> - selects <r>all red</> orbs with <b>s</> grade
    <b>alien</> <r>d</> <r>0</> - selects the <b>alien</> orb with <r>d</> grade that increases <r>attack</>.
    <o>c</> <dm>1</> - selects the boost stories of legend orb with grade <o>c</>
If you want to select <@q>all</> orbs then input:
    <@q>*</>
If you want to do <@q>multiple selections</> then separate them with a <@q>comma</> like this:
    <b>s</> <bl>black</> <g>4</>,<r>d</> <o>3</>,<g>floating</>

```
- JA:
```text

ヘルプ:
利用可能な等級: {all_grades_str}
利用可能なターゲット: {all_attributes_str}
利用可能な効果/能力: {all_effects_str}
<@w>注意: すべての属性で、すべての等級や効果が利用できるとは限りません。</>
入力例:
    <c>aku</> - <c>悪魔</> 本能玉をすべて選択
    <r>red</> <b>s</> - <b>s</> 等級の <r>赤い敵</> 本能玉をすべて選択
    <b>alien</> <r>d</> <r>0</> - <r>ダメージ</> アップ <r>d</> 等級の <b>エイリアン</> 本能玉を選択
    <o>c</> <dm>1</> - <o>c</> 等級のレジェンドストーリー強化本能玉を選択
<@q>すべて</> の本能玉を選択したい場合は、次のように入力してください:
    <@q>*</>
<@q>複数選択</> したい場合は、次のように <@q>カンマ</> で区切ってください:
    <b>s</> <bl>black</> <g>4</>,<r>d</> <o>3</>,<g>floating</>

```

### ?????????????????

- File: `files/edits/gamototo.properties`
- Keys: 43

#### `enter_raw_gamatoto_xp`

- Line: `1`
- EN:
```text
Enter Raw Gamatoto XP
```
- JA:
```text
ガマトトの生 XP を入力
```

#### `enter_gamatoto_level`

- Line: `2`
- EN:
```text
Enter Gamatoto Level
```
- JA:
```text
ガマトトのレベルを入力
```

#### `edit_gamatoto_level_q`

- Line: `3`
- EN:
```text
Enter an option to edit the gamatoto level:
```
- JA:
```text
ガマトトのレベルを編集するオプションを入力してください:
```

#### `gamatoto_xp`

- Line: `4`
- EN:
```text
Gamatoto XP
```
- JA:
```text
ガマトト XP
```

#### `gamatoto_level`

- Line: `5`
- EN:
```text
Gamatoto Level
```
- JA:
```text
ガマトト レベル
```

#### `gamatoto_level_success`

- Line: `6`
- EN:
```text
<@su>Succesfully set gamatoto level to <@s>{level}</> (XP: <@s>{xp}</>)</>
```
- JA:
```text
<@su>ガマトトのレベルを <@s>{level}</> に設定しました (XP: <@s>{xp}</>)</>
```

#### `gamatoto_level_current`

- Line: `7`
- EN:
```text
<@t>Current gamatoto level is <@q>{level}</> (XP: <@q>{xp}</>)</>
```
- JA:
```text
<@t>現在のガマトトレベルは <@q>{level}</> です (XP: <@q>{xp}</>)</>
```

#### `gamatoto_xp_level`

- Line: `8`
- EN:
```text
Gamatoto XP / Level
```
- JA:
```text
ガマトト XP / レベル
```

#### `current_gamatoto_helpers`

- Line: `10`
- EN:
```text
Current Helpers:
```
- JA:
```text
現在の隊員:
```

#### `gamatoto_helper`

- Line: `11`
- EN:
```text
Helper: <@t>{name}</> (rarity: <@t>{rarity_name}</>)
```
- JA:
```text
隊員: <@t>{name}</> (レアリティ: <@t>{rarity_name}</>)
```

#### `new_gamatoto_helpers`

- Line: `13`
- EN:
```text
New Helpers:
```
- JA:
```text
新しい隊員:
```

#### `gamatoto_helpers`

- Line: `14`
- EN:
```text
Gamatoto Helpers
```
- JA:
```text
ガマトト隊員
```

#### `ototo_cat_cannon`

- Line: `16`
- EN:
```text
Ototo Cat Cannon
```
- JA:
```text
オトート開発隊
```

#### `current_cannon_stats`

- Line: `18`
- EN:
```text
Current Cannon Stats:
```
- JA:
```text
現在の主砲ステータス:
```

#### `cannon_part`

- Line: `20`
- EN:
```text
<@t><@q>{name}</>{buffer}(level <@s>{level}</>)</>
```
- JA:
```text
<@t><@q>{name}</>{buffer}(レベル <@s>{level}</>)</>
```

#### `development`

- Line: `21`
- EN:
```text
{buffer}(Development: <@q>{development}</>)
```
- JA:
```text
{buffer}(開発状況: <@q>{development}</>)
```

#### `cannon_stats`

- Line: `22`
- EN:
```text
{parts}
```
- JA:
```text
{parts}
```

#### `foundation`

- Line: `24`
- EN:
```text
Foundation
```
- JA:
```text
土台
```

#### `style`

- Line: `25`
- EN:
```text
Style
```
- JA:
```text
装飾
```

#### `effect`

- Line: `26`
- EN:
```text
Effect
```
- JA:
```text
効果
```

#### `improved_foundation`

- Line: `27`
- EN:
```text
Improved Foundation
```
- JA:
```text
強化土台
```

#### `improved_style`

- Line: `28`
- EN:
```text
Improved Style
```
- JA:
```text
強化装飾
```

#### `unknown_stage`

- Line: `30`
- EN:
```text
Unknown Stage (<@s>{stage}</>)
```
- JA:
```text
不明な段階 (<@s>{stage}</>)
```

#### `selected_cannon`

- Line: `32`
- EN:
```text
<@t>Selected cannon: <@q>{name}</></>
```
- JA:
```text
<@t>選択中の主砲: <@q>{name}</></>
```

#### `selected_cannon_stage`

- Line: `33`
- EN:
```text
<@t>Cannon: <@q>{name}</> Current Stage: <@q>{stage}</></>
```
- JA:
```text
<@t>主砲: <@q>{name}</> 現在の段階: <@q>{stage}</></>
```

#### `cannon_edit_type`

- Line: `35`
- EN:
```text
Do you want to edit each cannon individually or apply edits to all selected cannons at once?:
```
- JA:
```text
各主砲を個別に編集しますか、それとも選択したすべての主砲へ一括適用しますか?:
```

#### `cannon_dev_level_q`

- Line: `37`
- EN:
```text
Do you want to edit the development of the cannons or the levels of the cannons?:
```
- JA:
```text
主砲の開発状況を編集しますか、それとも主砲レベルを編集しますか?:
```

#### `development_o`

- Line: `38`
- EN:
```text
Development
```
- JA:
```text
開発状況
```

#### `level_o`

- Line: `39`
- EN:
```text
Levels
```
- JA:
```text
レベル
```

#### `select_development`

- Line: `41`
- EN:
```text
Select development stage:
```
- JA:
```text
開発段階を選択:
```

#### `select_cannon`

- Line: `42`
- EN:
```text
Select Cannon
```
- JA:
```text
主砲を選択
```

#### `cannon_level`

- Line: `43`
- EN:
```text
Cannon Level
```
- JA:
```text
主砲レベル
```

#### `cannon_success`

- Line: `45`
- EN:
```text
<@su>Succesfully edited ototo cannons</>
```
- JA:
```text
<@su>主砲を編集しました</>
```

#### `cat_shrine`

- Line: `47`
- EN:
```text
Edit Cat Shrine
```
- JA:
```text
ネコ神社を編集
```

#### `shrine_level`

- Line: `48`
- EN:
```text
Edit Shrine Level
```
- JA:
```text
神社レベルを編集
```

#### `shrine_xp`

- Line: `49`
- EN:
```text
Shrine XP
```
- JA:
```text
神社 XP
```

#### `current_shrine_xp_level`

- Line: `50`
- EN:
```text
<@t>Current XP: <@q>{xp}</> (Level: <@q>{level}</>)</>
```
- JA:
```text
<@t>現在の XP: <@q>{xp}</> (レベル: <@q>{level}</>)</>
```

#### `cat_shrine_choice_dialog`

- Line: `51`
- EN:
```text
What do you want to do?:
```
- JA:
```text
何をしますか?:
```

#### `shrine_level_dialog`

- Line: `52`
- EN:
```text
Enter cat shrine level (max: <@q>{max_level}</>):
```
- JA:
```text
ネコ神社レベルを入力してください (最大: <@q>{max_level}</>):
```

#### `shrine_xp_dialog`

- Line: `53`
- EN:
```text
Enter cat shrine XP (max: <@q>{max_xp}</>):
```
- JA:
```text
ネコ神社 XP を入力してください (最大: <@q>{max_xp}</>):
```

#### `cat_shrine_edited`

- Line: `54`
- EN:
```text
<@su>Succesfully edited cat shrine</>
```
- JA:
```text
<@su>ネコ神社を編集しました</>
```

#### `make_catshrine_appear`

- Line: `55`
- EN:
```text
Show Cat Shrine in Game
```
- JA:
```text
ゲーム内にネコ神社を表示
```

#### `make_catshrine_disappear`

- Line: `56`
- EN:
```text
Hide Cat Shrine in Game
```
- JA:
```text
ゲーム内のネコ神社を非表示
```

### ???????

- File: `files/edits/gatya.properties`
- Keys: 8

#### `event_tickets`

- Line: `1`
- EN:
```text
Event Tickets / Lucky Tickets
```
- JA:
```text
イベントチケット / 福引チケット
```

#### `downloading_gatya_data`

- Line: `2`
- EN:
```text
Downloading gacha event data...
```
- JA:
```text
ガチャイベントデータをダウンロードしています...
```

#### `download_gatya_data_success`

- Line: `3`
- EN:
```text
<@su>Successfully downloaded gacha event data</>
```
- JA:
```text
<@su>ガチャイベントデータをダウンロードしました</>
```

#### `download_gatya_data_fail`

- Line: `4`
- EN:
```text
<@e>Failed to download gacha event data. Maybe try again</>
```
- JA:
```text
<@e>ガチャイベントデータのダウンロードに失敗しました。もう一度試してください</>
```

#### `save_gatya_error`

- Line: `5`
- EN:
```text
<@e>Failed to save gatya data due to {error}</>
```
- JA:
```text
<@e>{error} によりガチャデータを保存できませんでした</>
```

#### `gatya_by_id_q`

- Line: `6`
- EN:
```text
Do you want to select gacha banners by <@t>ID</> or <@t>name?</>:
```
- JA:
```text
ガチャバナーを <@t>ID</> と <@t>名前</> のどちらで選択しますか?:
```

#### `by_id`

- Line: `7`
- EN:
```text
By ID
```
- JA:
```text
ID で選択
```

#### `by_name`

- Line: `8`
- EN:
```text
By Name
```
- JA:
```text
名前で選択
```

### ?????? / ???????

- File: `files/edits/gold_pass.properties`
- Keys: 6

#### `gold_pass_dialog`

- Line: `1`
- EN:
```text
Enter the <@t>officer id</> you want (Leave <@q>blank</> for a <@q>random</> id, or enter <@q>-1</> to <@q>remove</> the gold pass):
```
- JA:
```text
使用したい <@t>officer id</> を入力してください (<@q>空欄</> で <@q>ランダム</> id、<@q>-1</> でゴールド会員を <@q>削除</>):
```

#### `gold_pass`

- Line: `2`
- EN:
```text
Gold Pass / Officer Club
```
- JA:
```text
ゴールド会員
```

#### `gold_pass_remove_success`

- Line: `3`
- EN:
```text
<@su>Succesfully removed the gold pass</>
```
- JA:
```text
<@su>ゴールド会員を削除しました</>
```

#### `gold_pass_get_success`

- Line: `4`
- EN:
```text
<@su>Succesfully gained the gold pass (id: <@t>{id}</>)</>. <@w>NOTE: The game may remove your gold pass if it realizes you don't actually have one, this is nothing I can fix so please do not report bugs about it.</>
```
- JA:
```text
<@su>ゴールド会員を取得しました (id: <@t>{id}</>)</>。<@w>注意: 実際には所持していないとゲーム側が判断した場合、ゴールド会員が削除されることがあります。これは修正できないため、この件のバグ報告はしないでください。</>
```

#### `officer_pass_fixed`

- Line: `5`
- EN:
```text
<@su>Succesfully fixed the officer club from crashing</>
```
- JA:
```text
<@su>にゃんこクラブのクラッシュを修正しました</>
```

#### `fix_officer_pass_crash`

- Line: `6`
- EN:
```text
Fix Officer Club Crashing
```
- JA:
```text
にゃんこクラブのクラッシュを修正
```

### ???

- File: `files/edits/enemy.properties`
- Keys: 17

#### `total_selected_enemies`

- Line: `1`
- EN:
```text
<@t>{total}</> enemies currently selected
```
- JA:
```text
現在 <@t>{total}</> 体の敵が選択されています
```

#### `unlock_enemy_guide_success`

- Line: `2`
- EN:
```text
<@su>Successfully unlocked enemy guide entries</>
```
- JA:
```text
<@su>敵図鑑の項目を解放しました</>
```

#### `remove_enemy_guide_success`

- Line: `3`
- EN:
```text
<@su>Successfully removed enemy guide entries</>
```
- JA:
```text
<@su>敵図鑑の項目を削除しました</>
```

#### `selected_enemy`

- Line: `4`
- EN:
```text
<@t>{name}</> (<@t>{id}</>) is selected
```
- JA:
```text
<@t>{name}</> (<@t>{id}</>) が選択されています
```

#### `select_enemies_valid`

- Line: `5`
- EN:
```text
Select all enemies in the enemy guide
```
- JA:
```text
敵図鑑に登録済みの敵をすべて選択
```

#### `select_enemies_invalid`

- Line: `6`
- EN:
```text
Select all enemies which are not in the enemy guide
```
- JA:
```text
敵図鑑に未登録の敵をすべて選択
```

#### `select_enemies_all`

- Line: `7`
- EN:
```text
Select all enemies
```
- JA:
```text
すべての敵を選択
```

#### `select_enemies_id`

- Line: `8`
- EN:
```text
Select enemies by ID
```
- JA:
```text
ID で敵を選択
```

#### `select_enemies_name`

- Line: `9`
- EN:
```text
Select enemies by name
```
- JA:
```text
名前で敵を選択
```

#### `select_enemies`

- Line: `10`
- EN:
```text
Select enemies:
```
- JA:
```text
敵を選択:
```

#### `enter_enemy_ids`

- Line: `11`
- EN:
```text
You can find enemy IDs here: <@t>https://battlecats.miraheze.org/wiki/Enemy_Release_Order</>\nEnter enemy IDs {{range_input}}:
```
- JA:
```text
敵 ID はここで確認できます: <@t>https://battlecats.miraheze.org/wiki/Enemy_Release_Order</>\n敵 ID を入力してください {{range_input}}:
```

#### `enter_enemy_name`

- Line: `12`
- EN:
```text
Enter enemy name:
```
- JA:
```text
敵の名前を入力してください:
```

#### `enemy_not_found_name`

- Line: `13`
- EN:
```text
<@w>No enemies found with name <@s>{name}</></>
```
- JA:
```text
<@w><@s>{name}</> という名前の敵は見つかりませんでした</>
```

#### `unlock_enemy_guide`

- Line: `14`
- EN:
```text
Unlock enemy guide entries
```
- JA:
```text
敵図鑑の項目を解放
```

#### `remove_enemy_guide`

- Line: `15`
- EN:
```text
Remove enemy guide entries
```
- JA:
```text
敵図鑑の項目を削除
```

#### `enemy_guide`

- Line: `16`
- EN:
```text
Enemy Guide
```
- JA:
```text
敵図鑑
```

#### `edit_enemy_guide`

- Line: `17`
- EN:
```text
Enter an option to edit enemy guide entries:
```
- JA:
```text
敵図鑑項目を編集するオプションを入力してください:
```

### ???????

- File: `files/edits/medals.properties`
- Keys: 8

#### `medals`

- Line: `1`
- EN:
```text
Meow Medals
```
- JA:
```text
にゃんこメダル
```

#### `add_medals`

- Line: `2`
- EN:
```text
Add Medals
```
- JA:
```text
メダルを追加
```

#### `remove_medals`

- Line: `3`
- EN:
```text
Remove Medals
```
- JA:
```text
メダルを削除
```

#### `medal_add_remove_dialog`

- Line: `4`
- EN:
```text
Do you want to <@t>add medals</> or <@t>remove medals</>?:
```
- JA:
```text
<@t>メダルを追加</> しますか、それとも <@t>メダルを削除</> しますか?:
```

#### `medal_string`

- Line: `5`
- EN:
```text
{medal_name}: <@q>{medal_req}</>
```
- JA:
```text
{medal_name}: <@q>{medal_req}</>
```

#### `select_medals`

- Line: `6`
- EN:
```text
Select medals:
```
- JA:
```text
メダルを選択:
```

#### `medals_added`

- Line: `7`
- EN:
```text
<@su>Succesfully added meow medals</>
```
- JA:
```text
<@su>にゃんこメダルを追加しました</>
```

#### `medals_removed`

- Line: `8`
- EN:
```text
<@su>Succesfully removed meow medals</>
```
- JA:
```text
<@su>にゃんこメダルを削除しました</>
```

### ?????

- File: `files/edits/missions.properties`
- Keys: 7

#### `missions`

- Line: `1`
- EN:
```text
Catnip Challenges / Missions|Cat Missions
```
- JA:
```text
ミッション
```

#### `complete_reward`

- Line: `2`
- EN:
```text
Clear Missions and Don't Claim Rewards
```
- JA:
```text
ミッションをクリア済みにして報酬は未受け取りにする
```

#### `complete_claim`

- Line: `3`
- EN:
```text
Complete Missions and Claim Rewards
```
- JA:
```text
ミッションをクリア済みにして報酬受け取り済みにする
```

#### `uncomplete`

- Line: `4`
- EN:
```text
Uncomplete Mission
```
- JA:
```text
ミッションを未クリアにする
```

#### `select_mission_claim`

- Line: `5`
- EN:
```text
Do you want to <@t>complete missions and don't claim the rewards</> or <@t>complete missions and claim the rewards <@q>(Doesn't actually give you the rewards)</></> or <@t>uncomplete missions if possible</>?
```
- JA:
```text
<@t>ミッションをクリア済みにして報酬は未受け取り</>、<@t>ミッションをクリア済みにして報酬受け取り済み <@q>(実際に報酬は付与されません)</></>、可能なら <@t>ミッションを未クリアにする</> のどれを行いますか?
```

#### `select_missions`

- Line: `6`
- EN:
```text
Select missions to edit:
```
- JA:
```text
編集するミッションを選択:
```

#### `missions_edited`

- Line: `7`
- EN:
```text
<@su>Succesfully edited missions</>
```
- JA:
```text
<@su>ミッションを編集しました</>
```

### ?????

- File: `files/edits/playtime.properties`
- Keys: 7

#### `playtime_str`

- Line: `1`
- EN:
```text
<@t>{hours}</> $(hours: !=1($hours)$, hour)/$, <@t>{minutes}</> $(minutes: !=1($minutes)$, minute)/$, <@t>{seconds}</> $(seconds: !=1($seconds)$, second)/$ (<@t>{frames} </>$(frames: !=1($frames)$, frame)/$)
```
- JA:
```text
<@t>{hours}</> 時間, <@t>{minutes}</> 分, <@t>{seconds}</> 秒 (<@t>{frames}</> フレーム)
```

#### `playtime_current`

- Line: `2`
- EN:
```text
Current playtime: {{playtime_str}}
```
- JA:
```text
現在のプレイ時間: {{playtime_str}}
```

#### `playtime_edited`

- Line: `3`
- EN:
```text
Successfully edited playtime to {{playtime_str}}
```
- JA:
```text
プレイ時間を {{playtime_str}} に編集しました
```

#### `playtime_hours_prompt`

- Line: `4`
- EN:
```text
Enter the number of <@t>hours</> to set the playtime to:
```
- JA:
```text
設定するプレイ時間の <@t>時間</> を入力してください:
```

#### `playtime_minutes_prompt`

- Line: `5`
- EN:
```text
Enter the number of <@t>minutes</> to set the playtime to:
```
- JA:
```text
設定するプレイ時間の <@t>分</> を入力してください:
```

#### `playtime_seconds_prompt`

- Line: `6`
- EN:
```text
Enter the number of <@t>seconds</> to set the playtime to:
```
- JA:
```text
設定するプレイ時間の <@t>秒</> を入力してください:
```

#### `playtime`

- Line: `7`
- EN:
```text
Play Time
```
- JA:
```text
プレイ時間
```

### ????????

- File: `files/edits/scheme_items.properties`
- Keys: 6

#### `scheme_items_edit_success`

- Line: `1`
- EN:
```text
<@su>Succesfully edited scheme items</>
```
- JA:
```text
<@su>外部報酬を編集しました</>
```

#### `scheme_items_select_gain`

- Line: `2`
- EN:
```text
Select scheme items to gain
```
- JA:
```text
入手する外部報酬を選択
```

#### `scheme_items_select_remove`

- Line: `3`
- EN:
```text
Select scheme items to remove
```
- JA:
```text
削除する外部報酬を選択
```

#### `gain_remove_scheme_items`

- Line: `4`
- EN:
```text
Do you want to <@t>gain</> or <@t>remove</> scheme items?:
```
- JA:
```text
外部報酬を <@t>入手</> しますか、それとも <@t>削除</> しますか?:
```

#### `gain_scheme_items`

- Line: `5`
- EN:
```text
Gain scheme items
```
- JA:
```text
外部報酬を入手
```

#### `remove_scheme_items`

- Line: `6`
- EN:
```text
Remove scheme items
```
- JA:
```text
外部報酬を削除
```

### ????? / ????

- File: `files/edits/special_skills.properties`
- Keys: 8

#### `special_skills_dialog`

- Line: `1`
- EN:
```text
Select a base ability to upgrade
```
- JA:
```text
強化する施設レベルを選択
```

#### `upgrade_individual_skill`

- Line: `2`
- EN:
```text
Input an upgrade for each selected skill
```
- JA:
```text
選択した各施設レベルの強化値を入力
```

#### `upgrade_all_skills`

- Line: `3`
- EN:
```text
Input an upgrade to apply to all selected skills
```
- JA:
```text
選択したすべての施設レベルに適用する強化値を入力
```

#### `upgrade_skills_select_mod`

- Line: `5`
- EN:
```text
Select an option to upgrade skills:
```
- JA:
```text
施設レベルを強化するオプションを選択してください:
```

#### `selected_skill`

- Line: `7`
- EN:
```text
<@t>{name}</> is selected
```
- JA:
```text
<@t>{name}</> が選択されています
```

#### `selected_skill_upgrades`

- Line: `8`
- EN:
```text
{{selected_skill}}: <@t>{base_level}<@s>+</>{plus_level}</>
```
- JA:
```text
{{selected_skill}}: <@t>{base_level}<@s>+</>{plus_level}</>
```

#### `selected_skill_upgraded`

- Line: `9`
- EN:
```text
<@t>{name}</> is upgraded to <@t>{base_level}<@s>+</>{plus_level}
```
- JA:
```text
<@t>{name}</> を <@t>{base_level}<@s>+</>{plus_level} に強化しました
```

#### `skills_edited`

- Line: `10`
- EN:
```text
<@su>Succesfully edited special skills</>
```
- JA:
```text
<@su>施設レベルを編集しました</>
```

### ?????????

- File: `files/edits/user_rank.properties`
- Keys: 9

#### `claim`

- Line: `1`
- EN:
```text
Claim
```
- JA:
```text
受け取り
```

#### `unclaim`

- Line: `2`
- EN:
```text
Unclaim
```
- JA:
```text
未受け取りに戻す
```

#### `fix_claimed`

- Line: `3`
- EN:
```text
Fix Claimed
```
- JA:
```text
受け取り状態を修正
```

#### `claim_or_unclaim_ur`

- Line: `4`
- EN:
```text
Do you want to <@t>claim</> or <@t>unclaim</> or <@t>fix claimed (unclaim any rewards that are above the current user rank)</> user rank rewards?:
```
- JA:
```text
ユーザーランク報酬を <@t>受け取り済み</>、<@t>未受け取り</>、または <@t>受け取り状態を修正 (現在のユーザーランクを超える報酬を未受け取りに戻す)</> のどれにしますか?:
```

#### `select_ur`

- Line: `5`
- EN:
```text
Select user rank rewards
```
- JA:
```text
ユーザーランク報酬を選択
```

#### `ur_claimed_success`

- Line: `6`
- EN:
```text
<@su>Successfully claimed user rank rewards</>
```
- JA:
```text
<@su>ユーザーランク報酬を受け取り済みにしました</>
```

#### `ur_unclaimed_success`

- Line: `7`
- EN:
```text
<@su>Successfully unclaimed user rank rewards</>
```
- JA:
```text
<@su>ユーザーランク報酬を未受け取りに戻しました</>
```

#### `ur_string`

- Line: `8`
- EN:
```text
Rank: <@s>{rank}</>: {description}
```
- JA:
```text
ランク: <@s>{rank}</>: {description}
```

#### `ur_fix_claimed_success`

- Line: `9`
- EN:
```text
<@su>Successfully fixed claimed user rank rewards</>
```
- JA:
```text
<@su>ユーザーランク報酬の受け取り状態を修正しました</>
```

### ?????

- File: `files/edits/fixes.properties`
- Keys: 9

#### `fix_gamatoto_crash`

- Line: `1`
- EN:
```text
Fix gamatoto from crashing the game
```
- JA:
```text
ガマトトでゲームがクラッシュする問題を修正
```

#### `fix_time_errors`

- Line: `2`
- EN:
```text
Fix time related issues
```
- JA:
```text
時間関連の問題を修正
```

#### `fix_ototo_crash`

- Line: `4`
- EN:
```text
Fix ototo from crashing the game
```
- JA:
```text
オトートでゲームがクラッシュする問題を修正
```

#### `fix_gamatoto_crash_success`

- Line: `6`
- EN:
```text
<@su>Sucessfully fixed gamatoto from crashing the game</>
```
- JA:
```text
<@su>ガマトトでゲームがクラッシュする問題を修正しました</>
```

#### `fix_time_errors_success`

- Line: `7`
- EN:
```text
<@su>Sucessfully fixed time related issues <@w>(Your device time on both devices must be correct for this to work)</></>
```
- JA:
```text
<@su>時間関連の問題を修正しました <@w>(これが動作するには、両方の端末で端末時刻が正しい必要があります)</></>
```

#### `fix_ototo_crash_success`

- Line: `8`
- EN:
```text
<@su>Successfully fixed ototo from crashing the game</>
```
- JA:
```text
<@su>オトートでゲームがクラッシュする問題を修正しました</>
```

#### `fixes`

- Line: `10`
- EN:
```text
Fixes
```
- JA:
```text
修正
```

#### `unlock_equip_menu`

- Line: `12`
- EN:
```text
Unlock Equip Menu
```
- JA:
```text
編成メニューを解放
```

#### `equip_menu_unlocked`

- Line: `13`
- EN:
```text
<@su>Successfully unlocked equip menu</>
```
- JA:
```text
<@su>編成メニューを解放しました</>
```

### ????/??????????

- File: `files/edits/gambling.properties`
- Keys: 3

#### `reset_wildcat_slots`

- Line: `1`
- EN:
```text
<@su>Successfully reset wildcat slots</>
```
- JA:
```text
<@su>にゃんこスロットリセットしました</>
```

#### `reset_cat_scratcher`

- Line: `2`
- EN:
```text
<@su>Successfully reset cat scratcher lottery</>
```
- JA:
```text
<@su>にゃんこスクラッチをリセットしました</>
```

#### `reset_gambling_events`

- Line: `3`
- EN:
```text
Reset Wildcat Slots and Cat Scratcher Lottery
```
- JA:
```text
にゃんこスロットとにゃんこスクラッチをリセット
```

