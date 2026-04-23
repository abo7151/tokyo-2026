# 2026-2027 Travel Itinerary Portal

一個精緻、響應式且具備安全保護的旅遊行程入口網站，用於整合規劃中的多個海外旅行計畫。

## 🌐 專案特色

- **高級視覺設計 (Swiss Style)**：採用 Inter 與 Noto Sans TC 字體系統，搭配 Stone (石灰色系) 與 Sky (天空藍) 的質感配色，營造專業且舒適的閱讀體驗。
- **動態行程分類**：首頁自動根據日期比對，將行程分類為「即將出發 (Upcoming)」與「過期回憶 (Past Memories)」。
- **安全存取控制**：
  - 使用 **Web Crypto API (SHA-256)** 進行密碼雜湊驗證，確保原始碼中不含明文密碼。
  - 導入 **Session Storage 記憶機制**，在同一個瀏覽器分頁中只需登入一次即可跨頁面自動解鎖。
- **豐富資訊架構**：整合了交通攻略、預算清單、海拔與氣溫變化圖表 (Chart.js) 以及互動式地圖 (Leaflet)。
- **完全響應式**：針對手機與平板進行深度優化，方便在旅途中隨時查閱。

## 📁 頁面結構

- `index.html`: 行程總覽入口，具備自動排序與狀態過濾功能。
- `swiss-2026.html`: 2026 瑞士家族深度旅遊 (包含海拔氣溫圖與精算方案)。
- `tokyo-2026.html`: 2026 東京春季之旅 (重點：哈利波特影城與黃金週攻略)。
- `kyushu-2027.html`: 2027 九州 ‧ 北海道跨區域銜接計畫 (鐵道迷專屬路線)。

## 🛠️ 技術棧

- **Frontend**: HTML5, Vanilla JavaScript
- **Styling**: Tailwind CSS (CDN), Lucide Icons, Font Awesome 6
- **Visualization**: Chart.js, Leaflet.js
- **Security**: SHA-256 Hashing via Web Crypto API

## 🚀 部署

本專案專為 **GitHub Pages** 靜態託管設計，直接推送至 `main` 分支即可完成自動部署。

---
*註：行程內容包含私人預算與聯絡資訊，存取時請輸入授權密碼。*
