# 🎓 教學駕駛艙集合 · Teaching Cockpits

> 互動式單頁教學網頁，以黑板粉筆風格設計，支援桌機 / 平板 / 手機。  
> 部署於 GitHub Pages，學生可直接用瀏覽器開啟學習。

🌐 **網站首頁**：https://truda0124.github.io/teaching-cockpits/

---

## 📁 目錄結構

```
teaching-cockpits/
├── index.html          ← 首頁（所有駕駛艙列表）
├── 社會/
│   └── CH4_1/          ← 五年級社會 CH4_1
│       ├── 教學駕駛艙_CH4_1.html
│       ├── CH4_1_簡報_第*.png   (11 張投影片)
│       ├── CH4_1_資訊圖表.png
│       └── CH4_1_黑板粉筆教學簡報.pdf
└── （未來新增科目資料夾）
```

## ✨ 功能特色

| 功能 | 說明 |
|------|------|
| 🖼 簡報輪播 | NotebookLM 生成投影片，支援觸控滑動 |
| 🔍 Lightbox | 點擊圖片全螢幕放大，支援縮放 25%–400% |
| 🎬 影片 | NotebookLM AI 影片（外開）或 YouTube 嵌入 |
| 🔊 語音 | NotebookLM AI Podcast 語音摘要（外開） |
| 📊 圖表 | 資訊圖表放大瀏覽 |
| ✏️ 評量 | 3–5 題記憶∕理解層次，即時對錯回饋 |
| 📱 響應式 | 桌機三欄 / 平板底部抽屜 / 手機單欄 |

## 🚀 新增駕駛艙

1. 在對應科目資料夾下建立新章節目錄
2. 放入 HTML 與圖片資源
3. 在 `index.html` 的對應區塊新增 `.cockpit-card`
4. `git add . && git commit -m "add 章節" && git push`
5. GitHub Pages 自動更新（約 1–2 分鐘）

## 🛠 製作工具

本系列駕駛艙使用 Claude AI + [teaching-cockpit skill](https://github.com/truda0124/teaching-cockpits) 自動生成。

---

*最後更新：2025年5月*
