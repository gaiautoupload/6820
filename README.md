# 6820 連訊｜主力雷達

本站是純 HTML、CSS、JavaScript 的靜態網站，以 data/snapshot.json 顯示 6820 興櫃加權均價、核心分點、買賣流向、觀察期推估成本與五日籌碼條件。正式來源是本目錄，GitHub 倉庫為 https://github.com/gaiautoupload/6820 。

對應的資料產生器在 ../6820_strategy。本機排程週一至週五 18:15 執行 update_website_scheduled.bat；通過每日 TPEx 分點與行情驗證後，重算快照並推送 main，由 GitHub Pages 發布。

觀察期從 2025-01-01 起，頁面上的成本、庫存和累積淨額只涵蓋這段可得歷史。分點行為不等於已確認的實質受益人；訊號是研究用的歷史條件判讀。
