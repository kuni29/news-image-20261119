# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/kuni29/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/kuni29/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

One image that sums up the world news of Thursday 19 November 2026, drawn as a newspaper front page: the date as the headline, then the day's six most consequential stories across regions and fields — the World Court's finding that Myanmar committed genocide against the Rohingya, Trump, Xi and Putin's joint peace declaration after the Shenzhen summit, tankers burning in the Strait of Hormuz as US–Iran strikes widen, Anthropic's record $81bn IPO pricing amid a deepening AI stock bust, a migrant boat capsizing off Senegal with dozens missing, and Barcelona's 6–0 Women's Champions League rout — plus a three-item "also today" strip. The picture is designed in `design.html` with hand-drawn SVG illustrations and rendered to `entry.png` by `render.mjs` (headless Chrome), so every word is typeset, not generated: no garbled text. `main.py` delivers the image bytes to the output directory, unchanged on every run.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Writes `out/entry.png` (1024×1024 PNG, under the 1 MiB cap).

---
<sub>Entered on [make.fun](https://make.fun/?ref=sjptyjw4&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
