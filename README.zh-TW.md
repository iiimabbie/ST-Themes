<div align="center">

[English](README.md) · [繁體中文](README.zh-TW.md) · [简体中文](README.zh-CN.md)

# ST Themes

**iiimabbie 的 SillyTavern 主題，匯入一次就會自動更新**

![Themes](https://img.shields.io/badge/themes-1-d9b8b4)
![SillyTavern](https://img.shields.io/badge/SillyTavern-theme-e8a87c)
![Theme Script](https://img.shields.io/badge/Theme%20Script-supported-a7b8c6)
![License](https://img.shields.io/badge/license-CC%20BY--NC--ND%204.0-lightgrey)

[主題](#主題) · [安裝方式](#安裝方式) · [運作方式](#運作方式) · [連結](#連結)

</div>

## 主題

<table>
  <tr>
    <td width="50%"><a href="dried-petal-tea/README.zh-TW.md"><img src="dried-petal-tea/screenshots/day.png" alt="Dried Petal Tea 白天模式"></a></td>
    <td>
      <h3><a href="dried-petal-tea/README.zh-TW.md">Dried Petal Tea</a></h3>
      乾燥玫瑰與霧霾藍的手繪風主題。藤蔓邊框、小花拉條、手繪圖示，頂欄右上角可以切換白天和黑夜。
    </td>
  </tr>
</table>

## 安裝方式

1. 打開主題資料夾，下載裡面的 `.json`。
2. 在 SillyTavern 開啟**使用者設定**，在**主題**旁點選**匯入**，選擇剛下載的檔案。
3. 有附腳本的主題（例如日夜切換）需要安裝 [Theme Script](https://github.com/iiimabbie/ST-ThemeScript)。沒有安裝也能使用，只是腳本不會執行。

> [!TIP]
> 第一次匯入有腳本的主題時，Theme Script 會顯示程式碼並詢問是否執行，同意後就不會再問。

## 運作方式

主題 JSON 的自訂 CSS 只有兩行，CSS 和腳本都從 GitHub Pages 載入：

```css
@import url("https://iiimabbie.github.io/ST-Themes/<主題>/<主題>.css");
<script src="https://iiimabbie.github.io/ST-Themes/<主題>/<主題>.css" data-run-at="early"></script>
```

主題更新後重新整理酒館就會套用，不需要重新匯入。GitHub Pages 有快取，更新後最多約 10 分鐘才會生效。

## 連結

- [Theme Script](https://github.com/iiimabbie/ST-ThemeScript)：讓主題可以執行 JavaScript 的擴充
- [Discord](https://discord.gg/P6kR5dpFVh)：提問與回報問題
- [Rainori Notion](https://classy-christmas-5c1.notion.site/Rainori-4188b3769594807babe7d3fd4074d118)：iiimabbie 的其他作品
