# 人生起跑線指數 · Life Starting Point Index

> 在你 18 歲以前，有幾項是你曾擁有的？勾選符合的項目，看看你的起跑線在哪裡。

**Live Demo:** https://startline.kdchang.cc

---

## 專案介紹

「人生起跑線指數」是一個輕量互動式測驗，透過 20 道題目衡量你在成長過程中所擁有的資源與機會。題目涵蓋三大面向：

| 面向 | 題數 | 說明 |
|------|------|------|
| 個人資源與教育 | 8 題 | 私人空間、設備、課外培訓、才藝等 |
| 家庭背景與資產 | 5 題 | 家庭學歷、財富規劃、居住地等 |
| 國際視野與機會 | 7 題 | 出國旅遊、海外教育、雙重國籍等 |

完成後會根據分數給出 Level 0–5 的評級，並顯示各面向的細項分數。

---

## 功能特色

- 即時累分：Sticky Score Bar 隨勾選即時更新
- 結果彈窗：動畫呈現分數、等級、三面向分解圖
- 分享功能：一鍵複製結果文字 / 分享至 X (Twitter)
- 無框架依賴：純 HTML + CSS + Vanilla JS，零依賴
- RWD：支援手機與桌機

---

## 快速開始

```bash
# clone 專案
git clone git@github.com:kdchang-labs/startline.git
cd startline

# 啟動本地開發伺服器
python3 -m http.server 8080
```

開啟瀏覽器前往 `http://localhost:8080`

---

## 專案結構

```
├── index.html        # 主頁面（含所有 CSS / JS）
├── images/
│   └── favicon.ico
└── CNAME             # GitHub Pages 自訂網域
```

---

## 評級對照表

| 分數 | 等級 | 標籤 |
|------|------|------|
| 0–3 | LEVEL 0 🌱 | 平民出身 |
| 4–7 | LEVEL 1 🏡 | 小康家庭 |
| 8–11 | LEVEL 2 🏙️ | 中產階級 |
| 12–14 | LEVEL 3 💼 | 優渥條件 |
| 15–17 | LEVEL 4 🌏 | 高度資源 |
| 18–20 | LEVEL 5 👑 | 頂層資源 |

---

## 致謝

靈感來源：[@swe_roger on Threads](https://www.threads.com/@swe_roger/post/DS1kWzLE-7F/)

---

## License

MIT
