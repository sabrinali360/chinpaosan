# 金寶山寵物殯葬品牌規格

來源：
- 客戶提供品牌色彩系統（2026-06-18 更新）
- 參考站：`https://www.memory.com.tw/`
- 本機參考：`/Users/limengying/Downloads/金寶貝/chinpaosan-pet-v2.html`
- sitemap：`/Users/limengying/Downloads/金寶貝/product/pet_funeral_sitemap_v5.html`

## 色彩 tokens

```css
:root {
  --bg:           #FFFFFF;   /* 白色背景 */
  --bg-soft:      #F8F8F8;   /* 區塊分隔底色 */
  --surface:      #F8F8F8;   /* 卡片底色 */
  --surface-2:    #EEEEEE;   /* 次層卡片 */
  --fg:           #2B2B2B;   /* 標題文字（深灰黑） */
  --fg-muted:     #666666;   /* 內文文字（中性灰） */
  --muted:        #BF9D5B;   /* 品牌金（主強調） */
  --muted-2:      #D8BE89;   /* 淺金色（hover/互動） */
  --border:       rgba(191, 157, 91, 0.22);  /* 細金線邊框 */
  --accent:       #BF9D5B;   /* 品牌金 CTA */
  --accent-strong:#D8BE89;   /* 品牌金 hover */
  --success:      #3a7d4a;
}
```

對應來源：
- `--bg` = `#FFFFFF` 白色網站背景
- `--bg-soft` / `--surface` = `#F8F8F8` 淺灰白區塊底
- `--fg` = `#2B2B2B` 深灰黑主標題
- `--fg-muted` = `#666666` 中性灰段落文字
- `--accent` / `--muted` = `#BF9D5B` 品牌金（主按鈕、重點標題）
- `--accent-strong` / `--muted-2` = `#D8BE89` 淺金色（Hover 互動）

## 字體堆疊

- Display: `"Noto Serif TC", "Iowan Old Style", "Times New Roman", serif`
- Body: `"Noto Sans TC", "PingFang TC", "Microsoft JhengHei", sans-serif`
- Mono: `"JetBrains Mono", "SFMono-Regular", ui-monospace, monospace`

## 版型姿態

1. 白色底首頁，大量留白，精緻排版，品牌金為唯一主強調色。
2. 導覽列白底半透明、細金線分隔，品牌名稱金色字，主 CTA 品牌金實色按鈕。
3. 標題使用襯線字深灰黑，內文中性灰，英數標籤保持大寫追字距。
4. 卡片白底搭配細金線邊框，圓角偏小（18–20px），陰影極輕。
5. 品牌金只用於：CTA 按鈕、重點數字、分類標籤、分隔線。不鋪滿整片區塊。
6. 區塊分隔用 `#F8F8F8` 灰底帶，取代舊版深色翻轉帶。

## 品牌核心精神

尊榮 · 紀念 · 永恆 · 溫暖 · 傳承 · 療癒
