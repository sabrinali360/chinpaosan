# chinpaosan

金寶山寵物生命禮儀網站 prototype。這個專案是純前端靜態展示，主要用來呈現首頁、影音專區與 AI 智能客服的互動流程，適合做提案展示、設計交付或後續正式網站開發的基礎。

## 專案內容

- `index.html`：首頁，包含品牌主視覺、服務介紹、空間展示、FAQ 與浮動 AI 助理入口。
- `video.html`：影音專區，包含主影片展示、影片分類、推薦清單與右下角 AI 助理。
- `ai-service.html`：AI 智能客服頁，展示情境分流、快捷提問、FAQ 篩選與模擬對話流程。
- `img/`：頁面使用的圖片素材。
- `DESIGN-HANDOFF.md`、`DESIGN-MANIFEST.json`：設計交接文件與畫面清單。
- `brand-spec.md`：品牌色彩、字體與視覺規格。

## 技術方式

- 純 HTML、CSS、原生 JavaScript
- 無建置流程
- 無框架依賴
- 可直接用瀏覽器開啟，或用本地 HTTP server 預覽

## 快速開始

直接開啟首頁：

```bash
open index.html
```

或啟動本地伺服器：

```bash
python3 -m http.server 8000
```

然後打開：

- `http://localhost:8000/index.html`
- `http://localhost:8000/video.html`
- `http://localhost:8000/ai-service.html`

## 互動功能

### 首頁

- 品牌導覽列與錨點跳轉
- 服務卡片與內容區塊展示
- 右下角浮動 AI 助理
- 預設問句快捷提問

### 影音專區

- 影片主視覺切換
- 類別篩選 chip
- 影片清單與推薦內容
- 與影音內容連動的 AI 助理抽屜

### AI 智能客服頁

- 使用情境分流
- 快捷提問按鈕
- FAQ 類別篩選
- 關鍵字驅動的模擬客服回覆

## 專案結構

```text
.
├── ai-service.html
├── index.html
├── video.html
├── img/
├── DESIGN-HANDOFF.md
├── DESIGN-MANIFEST.json
├── brand-spec.md
└── critique.json
```

## 已知注意事項

- 專案目前是 prototype，AI 客服回覆為前端寫死的模擬內容，尚未接後端或知識庫。
- 導覽與設計文件中有提到 `pet-funeral-home.html`，但目前 repo 內沒有這個檔案；現況以 `index.html` 作為首頁入口。
- 字型依賴 Google Fonts，離線環境下字體顯示可能與設計稿不同。

## 後續可擴充方向

- 串接真正的客服 API / RAG 知識庫
- 將 inline CSS / JS 拆分成獨立檔案
- 補上正式資料來源、影片內容與聯絡流程
- 納入部署流程與基本測試
