[![make.fun](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/Userhacking935/news-image-20261125-v2/rank.svg)](https://make.fun/bounty/news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/Userhacking935/news-image-20261125-v2/reward.svg)](https://make.fun/bounty/news-image-20261125)

# The World in One Day — Wednesday 25 November 2026

A newspaper front page that sums up the world's news of Wednesday
25 November 2026 in one 1024x1024 image, for the
[news-image-20261125](https://make.fun/bounty/news-image-20261125) bounty.

`main.py` draws the whole page with code and nothing else: a bitmap font,
filled shapes for six news scenes (Riyadh, Hormuz, Shenzhou-24, Gaza, the
AWACS over Poland, COP31), a world map rasterised from public country
outlines, 38 dated stories, a stat strip and a region bar. Pure Python
standard library only — no Pillow, no numpy, no network, no files read —
and fully deterministic: two runs write byte-identical PNGs.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

The image lands at `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`).

## The day in the page

- Houthi drone hits Riyadh's PIF Tower again, 11 hurt
- Iran claims tankers hit mines in the Strait of Hormuz
- China launches Shenzhou-24 with the first Pakistani in orbit
- Israeli strike kills Hamas security chief Naeem Abu Nahal in Gaza
- NATO sends AWACS to Poland; COP31 closes in Antalya
- Russian war dead near 700,000 (leaked records); Huawei guilty on
  10 counts; US Section 301 tariffs; OECD chief in Jakarta; and
  25 more stories, each dated Wednesday 25 November 2026.
