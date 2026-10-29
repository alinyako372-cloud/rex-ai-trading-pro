REX AI TRADING PRO — Free iPhone Web App Starter

This is a static front-end prototype. Prices and chart bars are sample data.
No live feed, AI model, signal calculation, backtest, push notification, or MT5 order execution is connected.

Use on iPhone:
1. Easiest local preview: download ZIP, open it in Files and preview index.html if iOS offers a preview. Some JavaScript/browser features may not work from a local file.
2. To publish for a Home Screen icon, upload index.html to a static host you control. GitHub Pages is free for public repositories but is intended for static websites and is not suitable for private credentials or a commercial SaaS.
3. Open the published HTTPS URL in Safari -> Share -> Add to Home Screen.

Next milestones:
- choose a permitted market-data provider and implement data freshness checks
- implement explicit, deterministic ICT/SMC rules and backtest with spread/slippage
- add server-side alert scheduling
- only later build a secure MT5 bridge / Expert Advisor and test on demo

Never include broker passwords or API secrets in front-end code. Do not use demo values to trade.
