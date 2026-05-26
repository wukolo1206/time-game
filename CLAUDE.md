---
project: time-game
category: 學科工具集
status: 穩定
version: "子專案文件初始化 2026-05-26"
url: https://wukolo1206.github.io/time-game/
next_action: 視需要確認 day24、units、calc 三個主要活動
updated: 2026-05-26
---

# CLAUDE.md — time-game

第八單元「時間」互動工具，支援一日 24 小時、時分秒換算、時分加減與學習單相關頁面。

## 技術框架

- 純 HTML + CSS + Canvas API + 原生 JavaScript
- 無 build 流程
- GitHub Pages 靜態部署

## 主要頁面

- `index.html`：導覽首頁
- `day24.html`：一日 24 小時
- `units.html`：時分秒換算
- `calc.html`：時分加減
- `word.html`：學習單/文字頁

## 不能動的地方

- 時鐘動畫與輸入流程容易互相影響，調整 UI 後也要測答案流程。
- `.bak` 與 DOCX 題目卷不要任意刪除。

## 部署後驗證清單

- 開啟 `https://wukolo1206.github.io/time-game/`。
- `day24.html` 可切換上午/下午/24 小時制。
- `units.html` 可進行單位換算。
- `calc.html` 可完成兩步驟輸入並顯示結果。
