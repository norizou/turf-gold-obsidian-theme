# Turf Gold — Obsidian Theme

競馬データの可視化にインスパイアされた洗練されたObsidianテーマ。深いターフグリーンと温かみのあるゴールドアクセントを特徴としています。ライトモードは明るいミントグリーンパレット、ダークモードは豊かなターフ色調を採用しています。

![Turf Gold Theme](https://img.shields.io/badge/Obsidian-Turf%20Gold-green) ![License](https://img.shields.io/badge/license-MIT-blue)

## スクリーンショット

*Coming soon*

## インストール

### 手動インストール

1. このリポジトリをダウンロード
2. 内容を展開
3. `Turf Gold` フォルダをObsidian Vaultの `.obsidian/themes/` ディレクトリにコピー
4. Obsidianで **設定 → 外観 → テーマ** を開く
5. テーマドロップダウンから **Turf Gold** を選択

### macOS / iCloud Vault

VaultがiCloud Drive上にある場合（例: `~/Library/Mobile Documents/iCloud~md~obsidian/Documents/`）：

```bash
# 一時ディレクトリにクローン
git clone https://github.com/norizou/turf-gold-obsidian-theme.git /tmp/turf-gold-obsidian-theme

# Vaultにコピー
cp -r /tmp/turf-gold-obsidian-theme/Turf\ Gold \
  ~/Library/Mobile\ Documents/iCloud~md~obsidian/Documents/.obsidian/themes/

# クリーンアップ
rm -rf /tmp/turf-gold-obsidian-theme
```

### グローバルインストール（全Vaultで使用）

すべてのVaultでこのテーマを使用する場合：

```bash
# Obsidianのグローバルテーマディレクトリにコピー
cp -r /path/to/turf-gold-obsidian-theme/Turf\ Gold \
  ~/Library/Application\ Support/obsidian/themes/

# 各Vaultにシンボリックリンクを作成
ln -s ~/Library/Application\ Support/obsidian/themes/Turf\ Gold \
  ~/path/to/vault/.obsidian/themes/Turf\ Gold
```

## カラーパレット

### ダークモード

| 要素 | 色 | 16進数 |
|------|------|--------|
| メイン背景 | Turf | `#0a1d15` |
| サイドバー背景 | Turf 2 | `#0e2519` |
| テキスト | Paper | `#f3eddd` |
| アクセント | Gold | `#c6a04e` |
| 成功 | Win | `#3aa978` |
| 警告 | Amber | `#dca23f` |
| エラー | Loss | `#d8505f` |

### ライトモード

| 要素 | 色 | 16進数 |
|------|------|--------|
| メイン背景 | Mint Green | `#eaf0ec` |
| サイドバー背景 | Mint Green 2 | `#e0eae2` |
| テキスト | Dark Green | `#142b18` |
| アクセント | Gold Deep | `#9a7a32` |
| 成功 | Win | `#3aa978` |
| 警告 | Amber | `#dca23f` |
| エラー | Loss | `#d8505f` |

## タイポグラフィ

- **本文**: システムフォント（San Francisco, Hiragino Sans, Yu Gothic, Meiryo）
- **見出し**: Obsidianデフォルト（font-familyオーバーライドなし）
- **等幅フォント**: SF Mono, Menlo, Consolas, Courier New

## カスタマイズ

このテーマはCSS変数を使用しているため、簡単にカスタマイズできます。CSSスニペットで色を上書きできます：

```css
/* Obsidian 設定 → 外観 → CSSスニペット → スニペット作成 */
.theme-dark {
  --background-primary: #your-color;
  --interactive-accent: #your-accent;
}
```

## ライセンス

MIT License — 自由に使用、変更、配布できます。

## 作者

[norizou](https://github.com/norizou)

