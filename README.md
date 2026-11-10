# 千葉大学管弦楽団 23卒団演奏会 ホームページ

2027年3月13日(土)・美浜文化ホールで開催する千葉大学管弦楽団23卒団演奏会の特設サイトです。

## ファイル構成

| ファイル | 内容 |
|---|---|
| `index.html` | ホーム(演奏会情報・お知らせ・更新履歴) |
| `program.html` | プログラム(ソロステージ・合奏ステージ) |
| `access.html` | アクセス(美浜文化ホールの地図・行き方) |
| `css/style.css` | 全ページ共通のデザイン |
| `img/` | 画像フォルダ(SNSのQRコード入り。ポスターもここに入れる) |

## 編集のしかた

各HTMLファイルの中に `▼▼▼ ここから〜編集部分 ▼▼▼` というコメントがあります。
その間のテキストを書き換えるだけで更新できます。

### まだ仮になっている箇所(要更新)

- [ ] 開場・開演時間(`index.html`)
- [ ] ソロステージの出演者・曲目(`program.html` の表に行を追加)
- [ ] お問い合わせ先メールアドレス(全ページのフッター、`example@example.com` を置換)
- [ ] ポスター画像(できたら `img/poster.jpg` として保存し、`index.html` の指示どおり差し替え)

### 色を変えたいとき

`css/style.css` の先頭にある `:root { ... }` の色コードを書き換えると、
サイト全体の配色が一括で変わります。

## 公開のしかた(GitHub Pages)

1. GitHubで **Organization** を作る
   - GitHub右上の「+」→「New organization」→ Freeプランを選択
   - 組織名がURLになる(例: `ourband-gradconcert` → `https://ourband-gradconcert.github.io`)
2. Organizationの中に `組織名.github.io` という名前の **公開リポジトリ** を作る
3. このフォルダのファイルを全部アップロードする(ブラウザからドラッグ&ドロップでもOK)
4. 数分後に `https://組織名.github.io` で公開される

### 更新するとき

- ブラウザの場合: GitHubでファイルを開いて鉛筆マーク → 編集 → 「Commit changes」
- 反映まで1〜2分かかることがあります

## 引き継ぎ(毎年必ずやること)

1. 次の代の担当者にGitHubアカウントを作ってもらう
2. Organizationの Settings → People → 「Invite member」で招待し、**RoleをOwnerにする**
3. 卒業する代はその後にOrganizationを抜ける

⚠️ **Ownerが誰もいなくなると二度と管理できなくなります。**
必ず「新Ownerを追加してから」抜けてください。
