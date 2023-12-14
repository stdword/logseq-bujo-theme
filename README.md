# <img align="top" width="40px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/icon.png"/> Logseq BuJo Theme
A theme for [logseq.com](https://logseq.com), inspired by Bullet Journals.

⚠️ This is the repository for themes **redesigning** and **adaptation** to new versions of Logseq. See `Credits` section for info about original author of all themes.

❗️ Required Logseq version ≥ `0.9.11`


## How it looks
||||
|:--:|:--:|:--:|
|*Light*|<img width="400px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/light-sepia.png"/><p>Sepia</p>|<img width="400px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/light-white.png"/><p>White</p>|
|*Dark*|<img width="400px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/dark-coffee.png"/><p>Coffee</p>|<img width="400px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/dark-black.png"/><p>Black</p>|

### Property icons
<img width="700px" src="https://github.com/stdword/logseq-bujo-theme/assets/1984175/e1c34367-5349-4559-afa4-68db922bd0be"/>


## Theme adds special tags to change appearance of blocks
### To hide tag reference: just start it with dot «.» sign
<img width="350px" src="https://github.com/stdword/logseq-bujo-theme/assets/1984175/bbc43d6c-2b0f-4d28-afee-14e379273d21"/>

### Column view: `#.columns` & `#.columns-fit`
<img width="500px" src="https://github.com/stdword/logseq-bujo-theme/assets/1984175/54288b01-878e-47cf-be01-574807ae872c"/>

### Border for block: `#.border`
<img width="350px" src="https://github.com/stdword/logseq-bujo-theme/assets/1984175/0fda5810-db21-4b25-b3d4-41b8c7cb5c89"/>

### Border for children blocks: `#.border-child`
<img width="350px" src="https://github.com/stdword/logseq-bujo-theme/assets/1984175/83c8bc6f-a0a0-4ce9-a198-7371dafbdfae"/>


## Installation
### From Logseq (recommended way)
* Click «...» and open the «Plugins» section (or press `t p`)
* Click on the «Marketplace»
* Select the «Themes» tab
* Search for «BuJo themes» and click install

  <img src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/marketplace1.png" width="403px" />
  <br>
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


## FAQ
### How to use themes on mobile devices?
1. Copy whole content of `src/base.css` to the bottom of `custom.css`
2. Copy whole content of selected theme (e.g. `src/dark-coffee.css`) to the bottom of `custom.css`
3. Remove line `@import './base.css';`

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
* [Copy code](https://github.com/vyleung/logseq-copy-code-plugin)
* [Block Calendar](https://github.com/vipzhicheng/logseq-plugin-block-calendar)
* [Days](https://github.com/sethyuan/logseq-plugin-days)
* [SmartBlocks](https://github.com/sawhney17/logseq-smartblocks)
* [Media Timestamp](https://github.com/sethyuan/logseq-plugin-media-ts)
* [Bullet Threading](https://github.com/pengx17/logseq-plugin-bullet-threading)
* [Tabbed Sidebar](https://github.com/sethyuan/logseq-plugin-tabbed-sidebar)

# Credits
* Original author of all themes — [@PiotrSss](https://github.com/PiotrSss/logseq-bujo-theme): `Copyright (c) 2021 Piotr Skarżyński`
* Some CSS from [logseq-flow-theme](https://github.com/nmartin84/logseq-flow): `Copyright (c) 2021 Nicholas Martin` (under [MIT License](https://github.com/nmartin84/logseq-flow/blob/f0a6dacfe8469a978c681dbafa98b3bf2625f180/LICENSE))
* Some CSS from [logtools](https://github.com/cannibalox/logtools): `Copyright (c) 2021 Phi` (under [MIT License](https://github.com/cannibalox/logtools/blob/79853d657f3b7d26469e685025de554cbd682e02/LICENSE))
* Coffee icon created by <a href="https://www.flaticon.com/free-icon/coffee_2954820" title="coffee icon">Smashicons</a>
