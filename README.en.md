[한국어](README.md) | English

# Three Kingdoms: 200 Key Places Interactive Map · 三國志 歷史地理 大圖鑑

> An interactive web atlas of the 200 most important places from the historical *Records of the Three Kingdoms* (三國志) and the novel *Romance of the Three Kingdoms* (三國演義). It runs in any browser with nothing to install.
>
> *Note: the app's interface and text are in Korean.*

**🔗 Live demo:** https://koala-penguin.github.io/three-kingdom-map/

---

## About

Luoyang, Xuchang, Red Cliffs, Chengdu and Wuzhang Plains come up again and again in the Three Kingdoms story. This map shows where each place actually was, what happened there, and which modern city it is today.

- **200 places**, ranked 1 to 200 by historical importance and fame.
- Every place has a **5-page detail card**:
  1. Overview & strategy
  2. Historical record (*Sanguozhi*)
  3. Story in the novel (*Romance*)
  4. Modern location
  5. Sources
- Every place lists its **modern administrative location**, e.g. Luoyang → Luoyang City, Henan, China.

## Features

### 🗺️ Interactive map
- Drag or touch to pan, and use the scroll wheel or pinch to zoom. More place cards appear as you zoom in.
- **Region shortcuts:**
  - Central Plains
  - Hebei & Liaodong
  - Guanzhong & Liang
  - Jiangdong & Huainan
  - All of China
- **Major rivers:** Yellow River, Yangtze, Han, Wei, Huai, and the Three Gorges.
- **Han-dynasty provinces:** the 13 provinces of the Later Han (Sili, Yu, Yan, Ji, Bing, You, Qing, Xu, Yang, Jing, Yi, Liang, Jiao), plus the Nanzhong region.
- **Faction colours:** Wei, Shu-Han and Wu strongholds each have their own colour.
- **Themes:** 🌙 dark mode and 📜 antique parchment mode.
- **Views:** split map + card view, or a 🗂️ grid of all 200 places.

### 🚩 Historical route tours
Seven guided tours that step through the key campaigns in order:
1. 🔥 Coalition against Dong Zhuo & Battle of Guandu (10 stops)
2. 🌊 Battle of Red Cliffs & the founding of the three kingdoms (9)
3. ⛰️ Liu Bei enters Shu & the Hanzhong campaign (9)
4. ⚔️ Guan Yu's Fancheng offensive & Battle of Yiling (8)
5. 🌟 Zhuge Liang's southern campaign & five Northern Expeditions (9)
6. 🛡️ Hefei, Ruxu & the Huainan front (6)
7. 🐎 Deng Ai's Yinping march & reunification under Jin (8)

### 🔍 Search, filter & sort
- **Filter by type:**
  - 🏯 Capitals & bases
  - ⚔️ Battlefields & strategic points
  - 🛡️ Passes & fortresses
  - 👑 Warlord territories
  - 📜 Hometowns & historic sites
- **Filter by rank band:** top 30, top 50, 51–100, 101–150, 151–200.
- **Sort by:** importance, reverse importance, Korean alphabetical order, or length of commentary.
- **People links:** click a person to find every place linked to them.
- **Extras:** ★ favourites and random place discovery.
- **Nearby strongholds:** straight-line distances (km) to neighbouring strongholds, with one-click jumps.

### 🔗 Sources
- Locations follow Tan Qixiang's *Historical Atlas of China* (中國歷史地圖集), Vol. 3.
- Distances were measured from Google Maps coordinates.
- Each place links to Wikipedia (Korean and Chinese), Namuwiki and Wikimedia Commons.

## Usage
- **Online:** open the link above.
- **Offline:** download `index.html` and open it in a browser. All images are embedded in the file, but the layout (Tailwind CDN) and fonts (Google Fonts) need an internet connection.
- **Devices:** works on desktop and mobile, including touch and pinch-zoom.

## Tech
- A single self-contained static file (`index.html`, ~5 MB). It needs no server and no build step.
- Built with HTML, Tailwind CSS and vanilla JavaScript.
- Images are embedded in the file as Base64.
- Hosted on GitHub Pages.

## Notes
- The history follows the official record (*Sanguozhi*). Events dramatised in the novel are kept separate, in the "Story in the novel" card.
- Scholars disagree on where some ancient sites were. If you spot an error, please open an Issue.
- Images and linked materials belong to their respective owners.
