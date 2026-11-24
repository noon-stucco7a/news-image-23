# news-image-23

[![make.fun bounty](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/noon-stucco7a/news-image-23/rank.svg)](https://make.fun/bounty/news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/noon-stucco7a/news-image-23/reward.svg)](https://make.fun/bounty/news-image-20261123)

One image that sums up the world's news of **Monday, 23 November 2026**:
a newspaper front page — "The World in One Page" — drawn programmatically
with PIL so every word is set in a real font and reads exactly.

The day's front page leads with the collapse of the COP31 climate summit
with no fossil-fuel deal, then Ukraine's sinking of a Russian warship off
Libya, Nvidia's reinstatement of Jensen Huang as CEO, the Indonesian
factory fire that killed 24, and FIFA's award of the 2031 Women's World
Cup to the US, Mexico, Costa Rica and Jamaica — with the Democrats' US
House win, the Manchester concert evacuation, and Bangladesh's vow to
arrest Sheikh Hasina in brief.

`main.ts` (Node 22, standard library only) copies the bundled `entry.png`
to the output path:

```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

License: MIT (see LICENSE).
