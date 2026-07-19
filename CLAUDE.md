# survival-war-of-probiotics — 專案藍圖

## 對話開始時請先讀
進度與最近更動都在 Obsidian：`2ndbrain/survival-war-of-probiotics/工作筆記.md`

一句話：**益生菌 vs 壞菌的生存戰爭網頁小遊戲**。

## 工作模式
- **加新工具/模組**：對 Claude 說「我想做一個 XXX」→ Claude 建 `tools/<名稱>/` 子資料夾並引導
- **結束工作**：對 Claude 說「**收工**」→ 自動 commit + push + 更新 Obsidian 工作筆記
- **接續工作**：對 Claude 說「**開工**」→ 讀工作筆記、報告 git 狀態、建議下一步

## 一桌三櫃
- 🪑 GDrive 工作桌：`G:\我的雲端硬碟\claude\projects\survival-war-of-probiotics\`（自動跨電腦同步）
- 🐙 GitHub repo：`jong-liu/survival-war-of-probiotics`（公開，網頁/程式碼的家）
- 📘 Obsidian 駕駛艙：`2ndbrain/survival-war-of-probiotics/工作筆記.md`（進度與想法的家）
- 🌐 GitHub Pages：`https://jong-liu.github.io/survival-war-of-probiotics/`
- 🔥 Firebase（選配）：要存資料（分數榜、存檔…）時才接

## 工具/模組清單
（之後新增時自動更新）
- （尚無）

## 工作注意事項
- commit 訊息寫清楚「做了什麼 + 為什麼」
- 機密（API key、token、個資）絕不進 repo
- 收工前說「收工」讓 Claude 同步三方
- GDrive 內 git 操作前先設 `git config windows.appendAtomically false`
