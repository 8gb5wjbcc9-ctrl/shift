# ShiftLink シフト管理アプリ（試作品）

## ファイル
- shift_app_login_prototype.html: HTML/CSS/JavaScriptを1ファイルにまとめたソースコードです。

## GitHub Pagesで公開する手順
1. GitHubで新しいリポジトリ（例: shiftlink）を作成します。
2. HTMLファイルをアップロードし、ファイル名を index.html に変更します。
3. リポジトリの Settings → Pages を開きます。
4. Deploy from a branch を選び、Branch を main、Folder を /(root) にして保存します。
5. 表示されるURLから公開ページを開けます。

## デモログイン
- 店長: LARGO-4821 / 1234
- バイト: tanaka01 / 1111

## 注意
このコードは画面試作用です。データは各ブラウザの localStorage に保存されます。
別々のスマホ間でデータは同期されません。デモ用ログイン情報は本番向けの安全な認証ではありません。
実運用には、認証・データベース・アクセス制御を備えたバックエンドが必要です。
