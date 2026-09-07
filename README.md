# yoin-log-legal

余韻ログ（iOS）の法務ページ。GitHub Pages で公開している。

- `index.html` — トップ（各ページへの導線・お問い合わせ）
- `privacy-policy.html` — プライバシーポリシー
- `terms-of-service.html` — 利用規約
- `tokushoho.html` — 特定商取引法に基づく表記

日本語／English を同一ページ内で切り替える。既定は端末の言語。

アプリ側は `--dart-define=PRIVACY_POLICY_URL=` / `TERMS_URL=` で
このサイトのURLを注入する（値は `yoin-log/ios/fastlane/.env`）。
