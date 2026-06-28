# wezterm-config

[WezTerm](https://wezfurlong.org/wezterm/) の個人設定（`.wezterm.lua`）。

## 内容

- テーマ: Ayu Mirage（背景は黒で上書き＋半透明）
- タイトルバー: OS バーを廃し、ウィンドウボタンをタブバーに統合（`INTEGRATED_BUTTONS`）
- Powerline 風タブ（アクティブタブを gold で強調）
- 右上ステータス: 実行中プロセス名 ＋ 時計
- 既定シェル: `wsl.exe`
- ペイン分割: `Ctrl+Shift+D`（横）/ `Ctrl+Shift+E`（縦）

## インストール

`.wezterm.lua` を WezTerm が読む場所に置く。

- Windows: `%USERPROFILE%\.wezterm.lua`（例: `C:\Users\<user>\.wezterm.lua`）
- Linux/macOS: `~/.wezterm.lua` または `~/.config/wezterm/wezterm.lua`

```sh
cp .wezterm.lua ~/.wezterm.lua
```

## 必要環境

- フォント: Cascadia Code（未導入なら自動で別フォントにフォールバック）
- Powerline グリフは WezTerm 内蔵の Symbols Nerd Font Mono が描画するため、別途 Nerd Font の導入は不要
