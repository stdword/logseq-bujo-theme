# ☕️ Logseq BuJo Theme
A theme for https://logseq.com, inspired by Bullet Journals.

⚠️ This is the repository for themes **redesigning** and **adaptation** to new versions of Logseq. See `Credits` section for info about original author of all themes.


## How it looks
||||
|:--:|:--:|:--:|
|*Light*|<img width="400px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/light-sepia.png"/><p>Sepia</p>|<img width="400px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/light-white.jpeg"/><p>White (will be [reviewed](https://github.com/stdword/logseq-bujo-theme/issues/2))</p>|
|*Dark*|<img width="400px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/dark-coffee.png"/><p>Coffee</p>|<img width="400px" src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/dark-black.png"/><p>Black</p>|


## Theme adds special tags to change appearance of blocks
### To hide tag reference: just start it with dot «.» sign
<img width="350px" src="https://github.com/stdword/logseq-bujo-theme/assets/1984175/bbc43d6c-2b0f-4d28-afee-14e379273d21"/>

### Column view: `#.columns` & `#.columns-fit`
<img width="500px" src="https://github.com/stdword/logseq-bujo-theme/assets/1984175/54288b01-878e-47cf-be01-574807ae872c"/>

### Column view: `#.border`
<img width="350px" src="https://github.com/stdword/logseq-bujo-theme/assets/1984175/0fda5810-db21-4b25-b3d4-41b8c7cb5c89"/>

### Column view: `#.border-child`
<img width="350px" src="https://github.com/stdword/logseq-bujo-theme/assets/1984175/83c8bc6f-a0a0-4ce9-a198-7371dafbdfae"/>


## Installation
### From Logseq (recommended way)
* Click «...» and open the «Plugins» section (or press `t p`)
* Click on the «Marketplace»
* Select the «Themes» tab
* Search for «BuJo theme» and click install

  <img src="https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/marketplace.png" width="400"/>
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
### How to disable dots in background?
* In Logseq: click «...» and open the «Settings» section (or press `t s`)
* Click «Edit custom.css»
* Add following lines to the end

  ```css
  #app-container {
    background-image: none !important;
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

# Credits
* Original author of all themes — [@PiotrSss](https://github.com/PiotrSss/logseq-bujo-theme): `Copyright (c) 2021 Piotr Skarżyński`
* Some CSS from [logseq-flow-theme](https://github.com/nmartin84/logseq-flow): `Copyright (c) 2021 Nicholas Martin` (under [MIT License](https://github.com/nmartin84/logseq-flow/blob/f0a6dacfe8469a978c681dbafa98b3bf2625f180/LICENSE))
* Some CSS from [logtools](https://github.com/cannibalox/logtools): `Copyright (c) 2021 Phi` (under [MIT License](https://github.com/cannibalox/logtools/blob/79853d657f3b7d26469e685025de554cbd682e02/LICENSE))
