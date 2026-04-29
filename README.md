# DRIFIX web page

DRIFIXの公開ページです。`privacy_policy.html` はGoogle Play等のプライバシーポリシーURLとして残しつつ、アプリ紹介、プロモーション画像、スクリーンショット、プライバシーポリシーを1ページに統合しています。

## Files

- `privacy_policy.html`: 紹介ページ兼プライバシーポリシー本体
- `index.html`: ルートURLから `privacy_policy.html` へ案内する入口
- `assets/promo/`: ヒーロー画像、OGP画像、アプリアイコン、船上ビジュアル
- `assets/screenshots/`: アプリ画面のWeb掲載用スクリーンショット

## Closed Test Form

クローズドテスト参加希望フォームはMicrosoft Formsへの外部リンクとして掲載しています。フォームを差し替える場合は、`privacy_policy.html` の `#closed-test` セクション内のURLを更新してください。

## Official Links

XとYouTubeは外部リンクとして掲載しています。差し替える場合は、`privacy_policy.html` の `#official-links` セクションとフッター内のURLを更新してください。

- X: `https://x.com/arcadia_`
- YouTube: `https://www.youtube.com/@tws1982`

## Screenshot Update

1. Androidエミュレータまたは実機でDRIFIXを起動します。
2. 同じ縦長比率でPNGスクリーンショットを取得します。
3. 個人情報、不要な座標、非公開の地名が写る場合は公開可能な表示に調整します。
4. Web掲載用は横幅700から900px程度へ縮小し、WebPを優先して保存します。
5. HTML側の `width` / `height` と `alt` を、差し替え後の画像に合わせて確認します。

現在の掲載名:

- `assets/screenshots/01-plan-map.webp`
- `assets/screenshots/02-condition-sheet.webp`
- `assets/screenshots/03-marine-dashboard.webp`
- `assets/screenshots/04-seat-recommendation.webp`
- `assets/screenshots/05-seat-analysis.webp`
- `assets/screenshots/06-hourly-timeline.webp`
- `assets/screenshots/07-calendar-overview.webp`
- `assets/screenshots/08-calendar-score-breakdown.webp`
- `assets/screenshots/09-seat-comparison-mode.webp`

外部フォント、外部JS、アクセス解析タグは追加していません。Microsoft Forms、X、YouTubeは外部リンクのみで、ページ内への埋め込みはしていません。
