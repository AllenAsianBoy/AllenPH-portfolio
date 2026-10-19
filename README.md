# ALLEN'S ART BASE v1.8

## 專案內容
保留 v1.7 記憶卡 Intro、中英切換、首頁及 My Time Machine 專案展示。

## YouTube 播放修正
- 點擊專案影片封面，才載入 YouTube iframe；提供外部 YouTube 觀看連結。
- 本機直接開啟 `file://` 時顯示提醒，避免將錯誤 153 誤判為影片損壞。
- 建議透過 `python -m http.server 8000`，再瀏覽 `http://localhost:8000/` 測試；或部署到 GitHub Pages 後測試。
- YouTube 的錯誤 153 與缺少 HTTP Referer / 用戶端識別有關。正式 HTTPS 網站仍可能受瀏覽器、擴充套件或影片嵌入限制影響。

## 圖片最佳化
- 7 張作品圖片由 JPG 轉為 WebP（品質設定 82；寬度最大 1920px）。
- 原 JPG 合計 2.13 MB；新 WebP 合計 1.08 MB。
- 保留原先的相對路徑 `assets/my-time-machine/`，適合 GitHub Pages 專案網站。
- 原始 JPG 請自行保存，不建議放入部署用儲存庫。

## 部署
將 `index.html` 和整個 `assets/` 資料夾放至 GitHub Pages 發布目錄。請勿只上傳 HTML。

## v1.9 Project sections
- 2D Concept Sketches: reserved for actual original concept sketches.
- 3D Environment Renders: existing six render images.
- Production Process: reserved for breakdowns, WIP and comparison images.
- All section labels and placeholder instructions support Chinese/English switching.


## v2.0 — Concept artwork

Added 11 optimized WebP concept sketches to `assets/my-time-machine/concepts/`. They are grouped into machine/prop and environment studies, with bilingual captions and full-size image links. Retain the whole `assets` directory when uploading to GitHub Pages.

## v2.4 製作過程圖片更新

製作過程原本的 6 張已移除，改為 3 張：前期場景配置、時光機概念與建模、模型拓樸與最佳化。圖片已轉為 WebP，並保留中英雙語標題、點擊大圖與延遲載入。

## v2.5 製作過程寬幅排版
- 03 / 製作過程三張 WebP 採用與 02 / 3D 場景渲染相同的全寬圖片展示方式。
- 移除白底、外框與固定比例裁切，保留 01 → 02 → 03 順序、中英圖說、延遲載入及點擊看大圖。


## PROJECT 002 模板
首頁新增 PROJECT 002 預留卡片與獨立詳細頁，含雙語內容、封面、職責、工具、影片和三個展示區塊。請將新素材放入 `assets/project-002/`，不要覆蓋 PROJECT 001 的圖片。


PROJECT 002: Robots In The Desert (3D Animation / 3D 動畫). Images, credits, software and video are placeholders pending real assets.
