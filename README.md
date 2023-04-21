# Logseq BuJo Theme
A theme for https://logseq.com, inspired by Bullet Journals.

⚠️ This is the repository for themes **redesigning** and **adaptation** to new versions of Logseq. See `Credits` section for info about original author of all themes.


## How it looks
### Coffee
![](https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/dark-coffee.png)
### White (will be reviewed soon)
![](https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/light-white.jpeg)
### Sepia
![](https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/light-sepia.png)
### Black
![](https://raw.githubusercontent.com/stdword/logseq-bujo-theme/main/assets/dark-black.png)


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


## How to turn off property icons?
In Logseq:
* Click «...» and open the «Settings» section (or press `t s`)
* Click «Edit custom.css»
* Add following lines to the end

  ```css
  .page-property-key::before {
      display: none;
  }
  ```


# Credits
* Original author of all themes — [@PiotrSss](https://github.com/PiotrSss/logseq-bujo-theme): `Copyright (c) 2021 Piotr Skarżyński`
* Some CSS from [logseq-flow-theme](https://github.com/nmartin84/logseq-flow): `Copyright (c) 2021 Nicholas Martin` (under [MIT License](https://github.com/nmartin84/logseq-flow/blob/f0a6dacfe8469a978c681dbafa98b3bf2625f180/LICENSE))
* Some CSS from [logtools](https://github.com/cannibalox/logtools): `Copyright (c) 2021 Phi` (under [MIT License](https://github.com/cannibalox/logtools/blob/79853d657f3b7d26469e685025de554cbd682e02/LICENSE))
