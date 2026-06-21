# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 專案說明

**網銀付款整批上傳** — 產生或處理網路銀行整批付款上傳檔的工具。

## 工作模式

- **加新功能**：對 Claude 說「我想做一個 XXX 功能」
- **結束工作**：對 Claude 說「**收工**」→ 自動 commit + push + 更新 Obsidian 工作筆記
- **接續工作**：對 Claude 說「**開工**」→ 讀工作筆記、報告 git 狀態、建議下一步

## 工作桌 + 三個家

- 📋 GDrive 工作桌：`G:\我的雲端硬碟\claude專案\網銀付款整批上傳\`
- 🐙 GitHub repo：`weiliangtao1995-design/bank-batch-payment`
- 📘 Obsidian 駕駛艙：`G:\我的雲端硬碟\2ndbrain\網銀付款整批上傳\工作筆記.md`

## 注意事項

- GDrive 內 git 必須保持 `windows.appendAtomically false`
- commit 前確認 `.claude/` 沒被加入（已在 `.gitignore`）
