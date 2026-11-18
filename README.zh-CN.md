<div align="center">

[English](README.md) · [繁體中文](README.zh-TW.md) · [简体中文](README.zh-CN.md)

# ST Themes

**iiimabbie 的 SillyTavern 主题，导入一次就会自动更新**

![Themes](https://img.shields.io/badge/themes-1-d9b8b4)
![SillyTavern](https://img.shields.io/badge/SillyTavern-theme-e8a87c)
![Theme Script](https://img.shields.io/badge/Theme%20Script-supported-a7b8c6)
![License](https://img.shields.io/badge/license-CC%20BY--NC--ND%204.0-lightgrey)

[主题](#主题) · [安装方式](#安装方式) · [工作原理](#工作原理) · [链接](#链接)

</div>

## 主题

<table>
  <tr>
    <td width="50%"><a href="dried-petal-tea/README.zh-CN.md"><img src="dried-petal-tea/screenshots/day.png" alt="Dried Petal Tea 白天模式"></a></td>
    <td>
      <h3><a href="dried-petal-tea/README.zh-CN.md">Dried Petal Tea</a></h3>
      干燥玫瑰与雾霾蓝的手绘风主题。藤蔓边框、小花滑块、手绘图标，顶栏右上角可以切换白天和黑夜。
    </td>
  </tr>
</table>

## 安装方式

1. 打开主题文件夹，下载里面的 `.json`。
2. 在 SillyTavern 打开**用户设置**，在**主题**旁点击**导入**，选择刚下载的文件。
3. 带脚本的主题（例如日夜切换）需要安装 [Theme Script](https://github.com/iiimabbie/ST-ThemeScript)。没有安装也能使用，只是脚本不会运行。

> [!TIP]
> 第一次导入带脚本的主题时，Theme Script 会显示代码并询问是否运行，同意后就不会再问。

## 工作原理

主题 JSON 的自定义 CSS 只有两行，CSS 和脚本都从 GitHub Pages 加载：

```css
@import url("https://iiimabbie.github.io/ST-Themes/<主题>/<主题>.css");
<script src="https://iiimabbie.github.io/ST-Themes/<主题>/<主题>.css" data-run-at="early"></script>
```

主题更新后刷新酒馆就会生效，不需要重新导入。GitHub Pages 有缓存，更新后最多约 10 分钟才会生效。

## 链接

- [Theme Script](https://github.com/iiimabbie/ST-ThemeScript)：让主题可以运行 JavaScript 的扩展
- [Discord](https://discord.gg/P6kR5dpFVh)：提问与反馈问题
- [Rainori Notion](https://classy-christmas-5c1.notion.site/Rainori-4188b3769594807babe7d3fd4074d118)：iiimabbie 的其他作品
