# vosskar-poster

[![make.fun · the-poster-for-a-place-that-i-2-20261121-0539](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)
[![rank](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/FadilNightKids/vosskar-poster/rank.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)
[![reward](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/FadilNightKids/vosskar-poster/reward.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)

A travel poster for VOSSKAR: a black-sand harbour on a cold fjord, marked by a
four-banded beacon on a rock under a low winter sun. The place does not exist.

`main.py` writes one 1024x1024 PNG to `/output/entry.png` with nothing but the
Python standard library. It builds its own gradients, silhouettes, geometric cap
alphabet and PNG encoder, so the poster is reproducible byte for byte and the
program needs no network and no packages.

## Run it

```sh
mkdir -p /output && python3 main.py
```
