# Pachimon

トランプ52枚で遊ぶ2人対戦カードゲーム（対AI）。Windows 配布版。
A 2-player card game played with a 52-card deck (vs AI). Windows build.

> 本リポジトリは **Windows 配布版（ダウンロード）の置き場**です。
> This repository hosts the **Windows distribution (downloads)**.

## ダウンロード / Download

最新版を [Releases](https://github.com/kken0507/pachimon-game/releases/latest) から入手してください。

1. `pachimon-windows-x64.zip` をダウンロード
2. 好きな場所に展開
3. `pachimon.exe` をダブルクリックして起動

Get the latest build from [Releases](https://github.com/kken0507/pachimon-game/releases/latest):

1. Download `pachimon-windows-x64.zip`
2. Unzip it anywhere
3. Double-click `pachimon.exe`

**動作環境 / Requirements:** Windows x64
**注意 / Note:** 同梱の `engine` フォルダ（`node.exe` / `stdio-main.cjs`）は削除しないでください。Do **not** delete the bundled `engine` folder.

## あそびかた / How to play

ホーム画面で対戦AIを左右キーで選び、**Enter** で試合開始。終了はホームの **QUIT** から（終了キーはありません）。
On the Home screen pick the AI with **Left/Right** and press **Enter** to start. Quit only via the **QUIT** item (there is no quit key).

### 操作（対戦中）/ Controls (in match)

| キー / Key | 動作 / Action |
|---|---|
| 矢印 / Arrows | カーソル移動 / move the cursor |
| Z / Enter | 決定（カード上で行動メニュー）/ confirm (opens card actions) |
| X | キャンセル / cancel |
| TAB | 左パネルのページ送り（札絵→効果）/ page the left panel (art → effect) |
| Ctrl+TAB | 効果 ⇔ ログ履歴 / effect ⇔ log history |
| ?(/) | 階段ガイド / stair guide |
| ESC | ポーズ（RESTART / NEW MATCH / HOME）/ pause |

詳しい操作・ルール・設定は、同梱の `README.txt` またはゲーム内の **HOW TO PLAY** を参照してください。
For full controls, rules and settings, see the bundled `README.txt` or the in-game **HOW TO PLAY**.

### 設定 / Settings

言語（ja / en）は **SETTINGS** で切替でき、**SAVE** で次回起動以降も保存されます。
The language (ja / en) can be changed in **SETTINGS** and kept across launches with **SAVE**.

## ルール / Rules

全カードの効果を含む詳しいルールブック(日本語 / English)はオンラインで読めます:
The full rulebook (including every card effect), in Japanese and English:

**https://kken0507.github.io/pachimon-game/**

（ゲーム内の **HOW TO PLAY** でも同じ内容を確認できます / the same content is available in-game under **HOW TO PLAY**）

## クレジット / Credits

- カード画像 / Card art: **Pixelart Cards** by kerenel (CC0) — https://kerenel.itch.io/pixelart-cards
