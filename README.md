<div align="center">

[English](README.md) · [繁體中文](README.zh-TW.md) · [简体中文](README.zh-CN.md)

# ST Themes

**SillyTavern themes by iiimabbie that update themselves after a single import**

![Themes](https://img.shields.io/badge/themes-1-d9b8b4)
![SillyTavern](https://img.shields.io/badge/SillyTavern-theme-e8a87c)
![Theme Script](https://img.shields.io/badge/Theme%20Script-supported-a7b8c6)
![License](https://img.shields.io/badge/license-CC%20BY--NC--ND%204.0-lightgrey)

[Themes](#themes) · [Installation](#installation) · [How it works](#how-it-works) · [Links](#links)

</div>

## Themes

<table>
  <tr>
    <td width="50%"><a href="dried-petal-tea/README.md"><img src="dried-petal-tea/screenshots/day.png" alt="Dried Petal Tea in day mode"></a></td>
    <td>
      <h3><a href="dried-petal-tea/README.md">Dried Petal Tea</a></h3>
      A hand-drawn theme in dried rose and misty blue, with vine borders, flower sliders and hand-drawn icons. Switch between day and night from the top-right corner of the top bar.
    </td>
  </tr>
</table>

## Installation

1. Open a theme folder and download its `.json` file.
2. In SillyTavern, open **User Settings**, click **Import** next to **Theme**, and choose the downloaded file.
3. Themes with scripts, such as the day/night switch, need [Theme Script](https://github.com/iiimabbie/ST-ThemeScript). Without it the theme still works, but its script does not run.

> [!TIP]
> The first time you import a theme with a script, Theme Script shows the code and asks whether to run it. Once you approve, it does not ask again.

## How it works

The theme JSON's Custom CSS has only two lines. Both the CSS and the script load from GitHub Pages:

```css
@import url("https://iiimabbie.github.io/ST-Themes/<theme>/<theme>.css");
<script src="https://iiimabbie.github.io/ST-Themes/<theme>/<theme>.css" data-run-at="early"></script>
```

When a theme is updated, reload SillyTavern to get it; there is no need to import it again. GitHub Pages caches files, so an update can take up to about 10 minutes to show.

## Links

- [Theme Script](https://github.com/iiimabbie/ST-ThemeScript): the extension that lets themes run JavaScript
- [Discord](https://discord.gg/P6kR5dpFVh): questions and bug reports
- [Rainori on Notion](https://classy-christmas-5c1.notion.site/Rainori-4188b3769594807babe7d3fd4074d118): other works by iiimabbie
