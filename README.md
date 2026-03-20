# Dropbox 介面切版 - 前端面試題目

## 題目

使用 **Vue 3** 實作 Figma 設計稿中的 Dropbox 檔案管理介面。

**設計稿**: https://www.figma.com/design/Uy9UGuFQqkPQJW8VWZjBNO/Dropbox-Redesign--Community-?node-id=2-20


## 技術要求

**必須使用**:
- Vue 3
- CSS（Tailwind CSS(優先) 或 原生 CSS）

**重要說明**:
- Desktop 版本仍要求 **pixel perfect**（誤差 < 5px）

---

## RWD 要求

- **Desktop (≥1024px)**: 依照 Figma，pixel perfect
- **Mobile (<768px)**: 自行設計

---

## 功能說明

### 必須實作的功能

0. 完整切版呈現 Figma 設計的畫面

1. **側邊欄的點擊**
   - 只需做到 Active 切換即可

2. **資料渲染**
   - 從 `data.json` 讀取資料動態渲染
   - 資料夾網格顯示前 6 個資料夾
   - Recent Files 表格顯示所有檔案

3. **使用者頭像顯示**
   - 顯示前 4-6 個頭像（重疊排列）
   - 超過的數量顯示為 "+N" 的圓形標籤

### 可選實作的功能

以下功能**不強制要求**，但實作可加分：

1. **搜尋功能** - 搜尋列可輸入並篩選檔案
2. **排序功能** - 點擊表頭可排序（Name, File Size, Last Modified）
3. **更多選項** - 三點選單的下拉功能(僅顯示假選單可自由發揮，無功能可)

