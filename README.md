# KEIBA AGENT v1.4.0

GitHub Pages向けの4ファイルです。ZIPを展開し、4ファイルをリポジトリの main ブランチ直下へアップロードしてください。ZIP自体をアップロードしてもサイトは更新されません。

- index.html: アプリ本体（v1.4.0、AI作戦会議、Cloudflare WorkerへのAPI接続フォーム）
- sw.js: Service Worker（キャッシュ名をv140に更新）
- manifest.webmanifest: ホーム画面アプリ設定
- README.md: この説明書

Cloudflare Worker側のGEMINI_API_KEYおよびテスト用トークンはZIPに含まれません。接続には公開済みWorker URLとテスト用合言葉が必要です。

既存の端末内データを守るため、更新前にアプリのJSONバックアップを保存してください。新バージョンでの実動作は公開後に確認してください。JRAデータ自動取得・公式結果照合などは実装済みとは限りません。
