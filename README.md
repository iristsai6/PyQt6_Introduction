# PyQt6 UI 與 QSS 現代化介面設計指南

專為 Python 開發者打造的 **PyQt6 UI 元件導覽與 QSS（Qt Style Sheets）風格設計指南**。透過現代化的響應式網頁介面，結合**互動預覽區**、**左右雙欄動態對應**與**原生風格模擬彈窗**，讓開發者在設計桌面應用程式外觀時，能更直覺地掌握各模組的實際渲染效果與 QSS 語法細節。

---

## 🚀 專案核心特色

* **首頁與導覽獨立架構**：首頁大氣呈現「主題風格預覽區」與「現代化視覺風格技巧」，詳細的 PyQt6 元件清單則集中收納於專屬的「元件分類資料庫」與「QSS 核心語法」中，避免畫面冗長繁雜。
* **左側按鈕連動右側即時預覽與 Code**：左側表格清單中的每個元件名稱皆為互動按鈕，點擊後右側會即時切換對應的畫面渲染效果與真實的 Python/QSS 程式碼。
* **原生風格自訂對話框 (Modal)**：模擬 PyQt6 桌面端應用程式的視覺風格，提供自訂的彈窗與對話框預覽（如 `QMessageBox` 與 `QFileDialog`），完美擺脫瀏覽器陽春的原生 `alert()`。
* **多佈局動態主題切換**：支援「科技藍 (Tech Blue)」、「極簡黑白 (Minimal Dark)」與「溫潤暖色 (Warm Orange)」等主題即時預覽。
* **Dark / Light 模式支援**：內建全站深色與淺色模式切換按鈕。

---

## 📂 專案檔案結構

```text
├── index.html         # 包含完整 HTML、Tailwind CSS 及互動 JavaScript 邏輯的主程式
└── README.md          # 專案說明文件
```

## 🛠️ 技術堆疊
前端框架：Tailwind CSS (CDN)

圖示庫：Font Awesome 6.4.0

字型設定：Inter (無襯線字型) & JetBrains Mono (程式碼等寬字型)

互動核心：原生 JavaScript ( DOM 操作、狀態管理與自訂 Modal 渲染 )

## 📦 快速開始與使用方式

點擊此連結開啟網站 > [PyQt6 指南針](https://iristsai6.github.io/PyQt6_Introduction/)

或將本專案的 index.html 檔案下載至您的電腦本機中

直接使用任意現代網頁瀏覽器（如 Chrome、Edge、Safari）雙擊開啟 index.html 即可立即瀏覽與互動

若您需要進行修改，可用任意程式碼編輯器（如 VS Code）開啟並編輯該檔案

## 📄 授權條款
本專案採用 MIT 授權條款進行釋出，歡迎自由取用與二次開發。