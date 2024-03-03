<h1>
<img align="top" width="40px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/icon.png"/>
Bullet Journals theme for Logseq
<a href="https://www.buymeacoffee.com/stdword">
  <img align="right" src="https://github.com/stdword/logseq13-full-house-plugin/blob/main/assets/coffee.png?raw=true" height="30px"/>
</a>
</h1>

<div align="left">

[![](https://img.shields.io/badge/status-support-da8202)](https://github.com/stdword/logseq-bujo-theme/releases)
[![Version](https://img.shields.io/github/v/release/stdword/logseq-bujo-theme?color=743b20)](https://github.com/stdword/logseq-bujo-theme/releases)
[![Downloads](https://img.shields.io/github/downloads/stdword/logseq-bujo-theme/total.svg?color=a0522d)](https://github.com/stdword/logseq-bujo-theme?tab=readme-ov-file#from-logseq-recommended-way)

</div>

A theme for [logseq.com](https://logseq.com), inspired by Bullet Journals.

⚠️ This is the repository for themes **redesigning** and **adaptation** to new versions of Logseq. See `Credits` section for info about original author of all themes.

❗️ Required Logseq version ≥ `0.9.11`

‼️ Logseq accent color is not supported and should be disabled:

<img width="516" alt="CleanShot 2024-03-03 at 04 13 37@2x" src="https://github.com/stdword/logseq-bujo-theme/assets/1984175/09a286d4-87d0-4a46-9364-631ddb0b2f64">


## How it looks
||||
|:--:|:--:|:--:|
|*Light*|<img width="400px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/light-sepia.png"/><p>Sepia</p>|<img width="400px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/light-white.png"/><p>White</p>|
|*Dark*|<img width="400px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/dark-coffee.png"/><p>Coffee</p>|<img width="400px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/dark-black.png"/><p>Black</p>|

### Property icons
<img width="700px" src="https://github.com/stdword/logseq-bujo-theme/assets/1984175/e1c34367-5349-4559-afa4-68db922bd0be"/>


## Installation
### From Logseq (recommended way)
* Click «...» and open the «Plugins» section (or press `t p`)
* Click on the «Marketplace»
* Select the «Themes» tab
* Search for «BuJo themes» and click install

 <img src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/marketplace1.png" width="403px" />
 <img src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/marketplace2.png" width="403px" />

* Close «Marketplace» and open «...» → «Themes» (or press `t i`) to bring up the theme selection window
* Select one with «BuJo» prefix
* To switch between Light and Dark themes press `t t`

### Manual way (in case of any troubles with recommended way)
* Download the latest theme release in a raw .zip archive from here and unzip it
* Enable «Developer mode» in «...» → Settings → Advanced
* Go to the «...» → Plugins, click «Load unpacked plugin» and point to the unzipped theme
* Enjoy the nice colors and work experience :)
* The only point here is: every new theme release should be also updated manually


## If you ❤️ what I'm doing — consider to support my work
<p align="left">
  <a href="https://www.buymeacoffee.com/stdword" target="_blank">
    <img src="https://github.com/stdword/logseq-bujo-theme/blob/main/assets/coffee.png?raw=true" alt="Buy Me A Coffee" height="60px" />
  </a>
</p>


## FAQ
### How to use themes on mobile devices?
1. In mobile Logseq: tap «...» and open the «Settings»
2. Tap «Edit custom.css»
3. Insert this code to the top of `custom.css`: <br/>
   Coffee:
   ```css
   @import url("https://raw.githack.com/stdword/logseq-bujo-theme/main/src/base.css");
   @import url("https://raw.githack.com/stdword/logseq-bujo-theme/main/src/dark-coffee.css");
   ```
   Black:
   ```css
   @import url("https://raw.githack.com/stdword/logseq-bujo-theme/main/src/base.css");
   @import url("https://raw.githack.com/stdword/logseq-bujo-theme/main/src/dark-black.css");
   ```
   Sepia:
   ```css
   @import url("https://raw.githack.com/stdword/logseq-bujo-theme/main/src/base.css");
   @import url("https://raw.githack.com/stdword/logseq-bujo-theme/main/src/light-sepia.css");
   ```
   White:
   ```css
   @import url("https://raw.githack.com/stdword/logseq-bujo-theme/main/src/base.css");
   @import url("https://raw.githack.com/stdword/logseq-bujo-theme/main/src/light-white.css");
   ```
4. Ensure Settings → General → Theme is Light for White and Sepia themes OR is Dark for Coffee and Black themes.

### How to disable dots in the background?

<img width="200px" src="https://github.com/stdword/logseq-bujo-theme/assets/1984175/7d79781f-642f-4dca-bf4b-1356823faa8d"/>

* In Logseq: click «...» and open the «Settings» section (or press `t s`)
* Click «Edit custom.css»
* Add following lines to the end

```css
#app-container {
  background-image: none !important;
}
```

### Where are `#.columns` & `#.columns-fit`, `#.border` & `#.border-child`?

These views was moved to [Missing Commands & Views](https://github.com/stdword/logseq13-missing-commands) plugin to be theme-independent.

### How to align dots in the background with distance between bullets of the adjacent levels?

<img width="200px" src="https://github.com/stdword/logseq-bujo-theme/assets/1984175/96679a60-4b88-44f3-a4b3-4f24e4d821fc"/>

* In Logseq: click «...» and open the «Settings» section (or press `t s`)
* Click «Edit custom.css»
* Add following lines to the end

```css
#app-container {
  background-position: -2.5px 0px;
  background-size: 30px 30px;
}
```

### How to turn off property icons?
* In Logseq: click «...» and open the «Settings» section (or press `t s`)
* Click «Edit custom.css»
* Add following lines to the end

```css
.page-property-key::before {
  display: none;
}
```


## Integrated with plugins:
* [Awesome Links](https://github.com/yoyurec/logseq-awesome-links)
* [Awesome Content](https://github.com/yoyurec/logseq-awesome-content)
* [Awesome Props](https://github.com/yoyurec/logseq-awesome-props)
* [Copy code](https://github.com/vyleung/logseq-copy-code-plugin)
* [Block Calendar](https://github.com/vipzhicheng/logseq-plugin-block-calendar)
* [Days](https://github.com/sethyuan/logseq-plugin-days)
* [SmartBlocks](https://github.com/sawhney17/logseq-smartblocks)
* [Media Timestamp](https://github.com/sethyuan/logseq-plugin-media-ts)
* [Bullet Threading](https://github.com/pengx17/logseq-plugin-bullet-threading)
* [Tabbed Sidebar](https://github.com/sethyuan/logseq-plugin-tabbed-sidebar)


# Credits
* Original author of all themes — [@PiotrSss](https://github.com/PiotrSss/logseq-bujo-theme): `Copyright (c) 2021 Piotr Skarżyński`
* [logseq-flow-theme](https://github.com/nmartin84/logseq-flow): `Copyright (c) 2021 Nicholas Martin`
* [logtools](https://github.com/cannibalox/logtools): `Copyright (c) 2021 cannibalox`
* [Awesome Content](https://github.com/yoyurec/logseq-awesome-content): `Copyright (c) 2023 yoyurec`
* Coffee icon created by <a href="https://www.flaticon.com/free-icon/coffee_2954820" title="coffee icon">Smashicons</a>
