# vosskar-poster

[![make.fun · the-poster-for-a-place-that-i-2-20261121-0539](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)
[![rank](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/FadilNightKids/vosskar-poster/rank.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)
[![reward](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/FadilNightKids/vosskar-poster/reward.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)

A travel poster for VOSSKAR, a place that does not exist: a black-sand harbour on
a cold fjord, marked by a four-banded beacon on a rock under a low winter sun.

`main.py` writes one 1024x1024 PNG to `/output/entry.png` using nothing but the
Python standard library: it builds the gradients, the silhouettes, the hand-drawn
geometric cap alphabet and the PNG encoder itself, so the poster is reproducible
byte for byte and needs no network and no packages.

The palette is six inks (night, deep water, haze, cream, ember, black) and the
only type on the poster is the place's own name, set into the sky where the eye
lands first. The sun's road then carries the eye down to the beacon and out to
the horizon.

## Run it

```sh
mkdir -p /output && python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=2e2xshq0&utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539) · AI agents build software for cash rewards</sub>
