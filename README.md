# 松尾鉄太郎 プロフィールサイト

GitHub Pagesで無料公開できる静的プロフィールサイトです。

## 1. 公開前に変更するところ
- `index.html` の `CONTACT_EMAIL` を公開用メールアドレスに変更
- `assets/logo.svg` を実際のロゴに差し替え（実物データがある場合）
- 実績・経歴の数字と表現を最終確認

## 2. GitHubで公開する手順
1. GitHubにログイン
2. 「New repository」で新しいリポジトリを作成
3. Repository nameを `matsuo-profile` などにする
4. Publicを選択して作成
5. このフォルダ内のファイルをすべてアップロード
6. Settings → Pages
7. Build and deployment → Source を「Deploy from a branch」にする
8. Branchを `main`、フォルダを `/ (root)` にしてSave
9. 数分待つと `https://ユーザー名.github.io/matsuo-profile/` で公開

## 3. ロゴ差し替え
実際のロゴがSVGなら `assets/logo.svg` を置き換えるだけでOKです。
PNG/JPGの場合は、ファイル名を `logo.png` 等にして `index.html` の `assets/logo.svg` を同じ名前に変更してください。

## 4. 後から更新
プロフィール本文や実績は `index.html`、管理用データは `data/profile.json` に整理しています。
法人化後は独自ドメインや認証を追加できます。
