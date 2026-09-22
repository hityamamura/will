# Will ｜ 総合型選抜専門道場

NO WILL, NO GROWTH. ― 意志なきところに、成長なし。

公開URL（予定）: https://hityamamura.github.io/will/

## 構成

```
index.html          サイト本体（1ファイル完結）
images/
  logo.png          ロゴ（背景を透過済み。必ず濃紺 #0E2143 の上に置くこと）
  hero-sea.jpg      ヒーロー背景
  yamamura.jpg      山村 和也（代表）
  kunihiro.jpg      国弘 紀子（師範）
  ohira.jpg         大平 啓朗（支部長）
  megaphone.jpg     行事セクション
  line-qr.png       公式LINE QRコード
.nojekyll           GitHub Pages が images/ をそのまま配信するための空ファイル
```

## 公開手順（GitHub Pages）

1. GitHub で新しいリポジトリ `will` を作成（Public）
2. このフォルダの中身をすべてアップロード
3. Settings → Pages → Source を「Deploy from a branch」、Branch を `main` / `(root)` に設定
4. 数分後 https://hityamamura.github.io/will/ で公開

## 更新するとき

- 日程・料金・文言はすべて `index.html` の中にあります
- 公式LINEのリンクは `https://page.line.me/582qmhnp`（3か所）

## 色

| 用途 | 値 |
|---|---|
| 群青（Will のベース） | `#0E2143` / `#1B3A6B` |
| 金（アクセント） | `#B08D57` |
| 生成り（背景） | `#FAF7F1` / `#F2EDE3` |
| 朱（ロゴの炎のみ） | `#D6262F` |

対話力カレッジは朱ベース、Will は群青ベース。次世代設計研究所と合わせて3サイトで一族に見えるよう、
書体（Noto Serif JP ＋ Noto Sans JP）と余白の取り方は共通にしています。
