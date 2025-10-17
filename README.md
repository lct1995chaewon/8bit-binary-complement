# 八位元二補碼互動教學（Eight‑Bit Two’s Complement Interactive Demo）

[![HTML5](https://img.shields.io/badge/HTML5-orange?logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-blue?logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-yellow?logo=javascript&logoColor=white)](#)

> 💡 使用語言：**HTML + CSS + Vanilla JavaScript（無框架）**

一個簡單易懂的網頁介面，用以說明 **「取反 + 加 1」** 的二補碼原理。  
學生可手動點擊 bit 位、觀察 8 位元二進制在取反與加 1 後對應的十進制變化。  

👉 [立即試玩 Demo （GitHub Pages 連結）](https://lct1995chaewon.github.io/8bit-binary-complement/)  


---

## 🎯 功能特色

- 互動式 **八位元 bit 方格**，點擊可即時切換 0 / 1。  
- 清楚分為兩步：
  1️⃣ 取反（只翻轉 bit，不顯示十進制）  
  2️⃣ 加 1（正式顯示最終二補碼結果）  
- 未完成第 1 步 時禁止進行第 2 步。  
- **完全前端**，不需要伺服器或外部函式庫。  
- 手機螢幕自適應設計。  

---

## 🧠 教學重點（概念）

在 8 位元二補碼表示中：

| 類別 | 說明 | 範例 |
|:--|:--|:--|
| 👍 正數 | 最高位 bit 為 0 → 直接二進制值 | `01111111` = +127 |
| 👎 負數 | 最高位 bit 為 1 → 整體值 − 256 | `11111111` = −1 |
| 🚀 轉換 | 取反 (b → ¬b) 再 + 1 | `01001000` (+72) → `10111000` (−72) |

---

## 🧩 檔案說明

| 檔案 | 用途 |
|:--|:--|
| `index.html` | 主互動網頁（內含 HTML、CSS、JS） |
| `README.md` | 專案說明文件（本檔案） |

---

## 🚀 如何使用

1. 在 GitHub 建立新倉庫，例如：`flipandadd1`  
2. 上傳 `index.html`  
3. 於 Settings → Pages → From branch 開啟 **GitHub Pages**  
4. 更新上方 Demo 連結  

---

## 🧩 範例畫面
*(可放上專案截圖，例如 `screenshot.png`)*  

---

## 📝 授權 License

本專案可自由使用於教學或學習目的。  
遵循 [MIT License](https://opensource.org/licenses/MIT)。

---

## 💬 English Summary

**Eight‑Bit Two’s Complement Interactive Demo**

A lightweight web page for teaching *invert + add‑one* binary logic.  
All implemented using plain HTML, CSS, and JavaScript — no frameworks.

**Features**
- Click‑to‑toggle bits  
- Two‑step process (invert → add one)  
- Step 2 disabled until Step 1 is done  
- Fully responsive for mobile learning  

---

👩‍💻 Maintainer ：*你的名字*｜ [@你的 GitHub 帳號](https://github.com/你的帳號)
