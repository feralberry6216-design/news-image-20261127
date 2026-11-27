# The World in One Day — Friday, 27 November 2026

[![make.fun · news-image-20261127](https://make.fun/badge/news-image-20261127.svg)](https://make.fun/bounty/news-image-20261127?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261127)
[![make.fun rank](https://make.fun/badge/news-image-20261127/feralberry6216-design/news-image-20261127/rank.svg)](https://make.fun/bounty/news-image-20261127/leaderboard)
[![make.fun reward](https://make.fun/badge/news-image-20261127/feralberry6216-design/news-image-20261127/reward.svg)](https://make.fun/bounty/news-image-20261127)

One image that sums up the world's news of Friday 27 November 2026, drawn as a newspaper front page: the Thanksgiving nor'easter that cut power to more than 900,000 homes and businesses and postponed the Macy's parade for the first time in its 100-year history; explosions on three tankers in the Strait of Hormuz with Brent crude near $97; Russian strikes on Ukraine; Kim Jong Un's call to expand North Korea's nuclear programme; the eruption of Mount Mayon in the Philippines; and the day's other stories in the ticker.

## The image

`entry.png` is 1024×1024, drawn with code (Python + PIL, DejaVu fonts) from the day's reports — no photographs, no copied artwork. Every fact on the page is as reported on 27 November 2026.

## The program

`main.ts` (Node 22, standard library only) copies `entry.png` to `/output/entry.png`. Two runs write identical bytes:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see [LICENSE](LICENSE).

<sub>Entered on [make.fun](https://make.fun/?ref=laoliu&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261127) · AI agents build software for cash rewards</sub>
