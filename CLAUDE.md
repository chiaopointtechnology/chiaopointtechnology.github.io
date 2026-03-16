# CLAUDE.md

## 專案概述

**喬點科技 CHIAOPOINT TECHNOLOGY LLC** — AI 公司組織規劃與工具（Wyoming LLC）

### 網站（GitHub Pages）
- 帳號：`chiaopointtechnology`
- 網址：https://chiaopointtechnology.github.io
- Repo：https://github.com/chiaopointtechnology/chiaopointtechnology.github.io

### 頁面

| 檔案 | 說明 | 網址 |
|------|------|------|
| `index.html` | 公司首頁（核心價值、聯絡方式、多語系 EN/中/日） | /index.html |
| `products.html` | 產品展示（PAP、ClosetTime、CCeSIM、FoodMODAPP） | /products.html |
| `prompts.html` | 方案中心（10 分類、70+ 方案模板與 AI 指令） | /prompts.html |
| `snaporder-mindmap.html` | SnapOrder AI 互動式架構心智圖（單店版 vs 連鎖版） | /snaporder-mindmap.html |
| `office.html` | 像素風格虛擬辦公室（RPG 動畫） | /office.html |
| `privacy.html` | 隱私政策 | /privacy.html |
| `terms.html` | 服務條款 | /terms.html |

### 方案中心分類（prompts.html）

| 分類 | 內容 |
|------|------|
| App 開發 | SwiftUI 新頁面、修 Bug、UI 調整、功能開發、動畫、Firebase、多語系 |
| App Store 上架 | Build 上傳、審查回覆、ASO 優化、截圖、IAP |
| 網站製作 | 單頁網站、Landing Page、隱私政策、GitHub Pages、資料視覺化 |
| 商業文件 | 客戶提案、商業計劃、合作信、客戶回覆、簡報 |
| 行銷社群 | IG 貼文、限動、產品文案、招募文、SEO |
| 自動化流程 | n8n 工作流、批次處理、備份、Claude API |
| Claude Code 指令 | /foodmod-single、/foodmod-chain、/new-view、/art、/list |
| **AI 應用方案** | **餐飲 AI 智慧叫貨（架構、預測引擎、防範機制、LINE版、SMS版、Prompt）** |
| **SnapOrder AI** | **專案架構（14張卡片：系統介紹、檔案結構、單店/連鎖架構、WF1-WF5、技術堆疊、資料結構、成本定價、市場策略、心智圖、開發教訓）** |
| 學習專區 | Claude Code、Node.js、GitHub、API、Git、MCP、Hooks、SDK、Skills |

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

### prompts.html（方案中心）
- 配色：米色 `#f5f2ed`、深色文字 `#1a1a1a`、強調色 `#c44b2b`
- 字體：DM Serif Display + Space Grotesk + Noto Sans TC
- 風格：簡約藝術、Readymag 風格

### index.html / products.html（公司首頁）
- 配色：白底 `#ffffff`、粉色 `#E8A0B4`、薄荷 `#8FBFB4`
- 字體：Roboto + Space Mono + Noto Sans TC/JP
- 支援深色模式、多語系（EN/中/日）

## 部署方式

```bash
cd "/Users/CHIAO/Desktop/我的專案/AI-Company-Plan"
git add -A && git commit -m "update" && git push
```

注意：gh CLI 需先登入 chiaopointtechnology 帳號（`gh auth switch --user chiaopointtechnology`）

## 重要注意

- 使用者非工程背景，請用白話解釋
- 改 code 前先確認
- 方案中心的目的：讓非技術人員也能瀏覽喬點科技的所有應用方案與 AI 工具
