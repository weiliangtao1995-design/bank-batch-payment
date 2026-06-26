# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 專案說明

**網銀付款整批上傳** — 產生或處理網路銀行整批付款上傳檔的工具。
型態：純前端 HTML（SheetJS / xlsx.full.min.js），本機開 `index.html` 或雙擊 `銀行整批付款工具.bat` 使用，無後端、無資料庫。
所屬：「我的工具箱」多 repo 模式的一個工具（容器藍圖見 `claude專案\CLAUDE.md`）。

## 工作模式

- **加新功能**：對 Claude 說「我想做一個 XXX 功能」
- **結束工作**：對 Claude 說「**收工**」→ 自動 commit + push + 更新 Obsidian 工作筆記
- **接續工作**：對 Claude 說「**開工**」→ 讀工作筆記、報告 git 狀態、建議下一步

## 工作桌 + 三個家

- 📋 GDrive 工作桌：`G:\我的雲端硬碟\claude專案\網銀付款整批上傳\`
- 🐙 GitHub repo：`weiliangtao1995-design/bank-batch-payment`（**私有**，不上 GitHub Pages）
- 📘 Obsidian 駕駛艙：`G:\我的雲端硬碟\2ndbrain\網銀付款整批上傳\工作筆記.md`

## 注意事項（財會資料安全）

- 🔒 **真實財務資料一律不進版控**：真實銀行帳號、付款金額明細、員工真名、薪資、網銀憑證／金鑰。測試一律用假帳號／代號。
- 🔒 repo 是私有的，但**私有不是保險箱**，敏感真實資料仍不該 commit。
- GDrive 內 git 必須保持 `windows.appendAtomically false`。
- commit 前確認 `.claude/` 沒被加入（已在 `.gitignore`，含可能記錄 token 的 `settings.local.json`）。
