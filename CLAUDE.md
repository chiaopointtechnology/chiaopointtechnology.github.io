# CLAUDE.md

## 專案概述

**喬點科技 ChiaoPoint Technology** — AI 公司組織規劃與工具

### 網站（GitHub Pages）
- 帳號：`chiaopointtechnology`
- 網址：https://chiaopointtechnology.github.io
- Repo：https://github.com/chiaopointtechnology/chiaopointtechnology.github.io

### 頁面

| 檔案 | 說明 | 網址 |
|------|------|------|
| `index.html` | 組織藍圖（6部門、18 AI 模組、4 產品線） | /index.html |
| `office.html` | 像素風格虛擬辦公室（RPG 動畫） | /office.html |
| `prompts.html` | AI 指令庫（6 分類、30+ 指令模板） | /prompts.html |

### AI 指令庫分類

| 分類 | 內容 |
|------|------|
| App 開發 | SwiftUI 新頁面、修 Bug、UI 調整、功能開發、動畫、Firebase、多語系 |
| App Store 上架 | Build 上傳、審查回覆、ASO 優化、截圖、IAP |
| 網站製作 | 單頁網站、Landing Page、隱私政策、GitHub Pages、資料視覺化 |
| 商業文件 | 客戶提案、商業計劃、合作信、客戶回覆、簡報 |
| 行銷社群 | IG 貼文、限動、產品文案、招募文、SEO |
| 自動化流程 | n8n 工作流、批次處理、備份、Claude API |

### n8n 自動化工作流（未部署）

| 檔案 | 用途 |
|------|------|
| `n8n-workflows/01-new-client-flow.json` | 新客戶自動建檔通知 |
| `n8n-workflows/02-content-publishing.json` | 內容自動發布 |
| `n8n-workflows/03-dev-deploy.json` | 開發部署通知 |
| `n8n-workflows/04-meeting-notes.json` | 會議紀錄自動整理 |
| `n8n-workflows/05-weekly-report.json` | 週報自動產生 |

---

## 設計風格

- 配色：米色 `#f5f2ed`、深色文字 `#1a1a1a`、強調色 `#c44b2b`
- 字體：DM Serif Display + Space Grotesk + Noto Sans TC
- 風格：簡約藝術、Readymig 風格

## 部署方式

```bash
cd "/Users/CHIAO/Desktop/我的專案/AI-Company-Plan"
git add -A && git commit -m "update" && git push
```

注意：gh CLI 需先登入 chiaopointtechnology 帳號（`gh auth switch --user chiaopointtechnology`）

## 重要注意

- 使用者非工程背景，請用白話解釋
- 改 code 前先確認
- 指令庫的目的：讓非技術人員也能精準使用 AI
