# ✨ 夢幻計算機大全 — Calcorama

72 種免費線上計算機，涵蓋數學、財務、健康、日期、工程等 9 大類別。
無廣告・無需登入・所有計算在瀏覽器本地執行。

🌐 **Live site:** https://calc.sotshau.fun

---

## 類別一覽

| 類別 | 計算機數量 |
|------|-----------|
| 🔢 數學與科學 | 12 |
| 💰 財務金融 | 14 |
| 💪 健康身體 | 10 |
| 📅 日期時間 | 8 |
| 🎓 學業成績 | 4 |
| 🏠 生活實用 | 8 |
| ⚙️ 工程程式 | 5 |
| 🎉 趣味社交 | 6 |
| 📐 幾何空間 | 5 |

---

## 技術架構

- **Vanilla HTML / CSS / JavaScript** — 無框架、無依賴、無建置工具
- **Glassmorphism UI** — 毛玻璃風格設計，動態漸層背景
- **全本地執行** — 不傳送任何資料至外部伺服器
- **Google Fonts** — Nunito 字型（CDN 載入）

## 專案結構

```
calcorama/
├── index.html                  # 首頁（含搜尋功能）
├── calculator.html             # 基本四則計算機
├── about.html                  # 關於本站
├── robots.txt
├── sitemap.xml
└── calculators/
    ├── math/                   # 數學與科學（12 個）
    ├── finance/                # 財務金融（14 個）
    ├── health/                 # 健康身體（10 個）
    ├── date/                   # 日期時間（8 個）
    ├── school/                 # 學業成績（4 個）
    ├── life/                   # 生活實用（8 個）
    ├── engineering/            # 工程程式（5 個）
    ├── fun/                    # 趣味社交（6 個）
    └── geometry/               # 幾何空間（5 個）
```

## 本地執行

直接在瀏覽器開啟任何 HTML 檔案，或使用靜態伺服器：

```bash
python3 -m http.server 8080
# 然後開啟 http://localhost:8080
```

## 🤖 AI 協助建置

本站由 [Anthropic Claude](https://www.anthropic.com/claude)（claude-sonnet）協助建置，包含程式碼撰寫、UI 設計與 SEO 設定。所有程式碼均由人工審閱確認。
