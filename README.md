# NG Terminal

One page, one tab per natural-gas tool. Each tab embeds the live GitHub Pages site of its own repo, so
nothing here runs on a schedule: the tools keep updating themselves and this page shows them.

**Live page:** https://optaimumsolutions.github.io/ng-terminal/

| Tab | Source repo | Updates |
|---|---|---|
| Weather / HDD (`#hdd`, F1) | [gas-hdd](https://github.com/optaimumsolutions/gas-hdd) | 4x daily from NOAA GEFS |
| COT Positioning (`#cot`, F2) | [cot-electricity](https://github.com/optaimumsolutions/cot-electricity) | weekly, after the CFTC Friday release |

To add a tab: append an entry to `TABS` in `index.html` (id, key, title, sub, url, optional `status()`).
