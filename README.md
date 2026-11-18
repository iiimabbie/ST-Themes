# ST Themes

iiimabbie 的 SillyTavern 主題。每個主題一個資料夾，CSS 由 GitHub Pages 提供，主題 JSON 只引用網址，改 CSS 後不必重新匯入。

## 主題

| 主題 | 說明 |
| --- | --- |
| [Dried Petal Tea](dried-petal-tea/) | 乾燥玫瑰與霧霾藍的手繪風主題，白天／黑夜可切換 |

## 使用方式

1. 安裝 [ST-ThemeScript](https://github.com/iiimabbie/ST-ThemeScript)（日夜切換等腳本需要它；沒裝也能用，只是腳本不會執行）。
2. 下載主題資料夾裡的 `.json`，在 SillyTavern 的「使用者設定 → 主題」匯入。

## 資料夾結構

```
<主題名稱>/
  <主題名稱>.css   主題 CSS；需要腳本時，把 <script>...</script> 放在檔案最後
  *.json           SillyTavern 主題檔，custom_css 只放下面兩行
```

```css
@import url("https://iiimabbie.github.io/ST-Themes/<主題名稱>/<主題名稱>.css");
<script src="https://iiimabbie.github.io/ST-Themes/<主題名稱>/<主題名稱>.css" data-run-at="early"></script>
```

## 授權

[CC BY-NC-ND 4.0](LICENSE)：可以自己修改來用；分享原版要標明作者，不能商用，修改後的版本不能分享。
