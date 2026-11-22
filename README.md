# Honey — The Picture That Tastes of One Ingredient

[![make.fun · the-picture-that-tastes-of-one-20261122-2047](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047?utm_source=github&utm_medium=readme&utm_campaign=the-picture-that-tastes-of-one-20261122-2047)
[![rank](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047/yuyan5319-crypto/makefun-the-picture-that-tastes-of-one-20261122-2047/rank.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-picture-that-tastes-of-one-20261122-2047)
[![reward](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047/yuyan5319-crypto/makefun-the-picture-that-tastes-of-one-20261122-2047/reward.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047?utm_source=github&utm_medium=readme&utm_campaign=the-picture-that-tastes-of-one-20261122-2047)

The brief allows a single ingredient, and this picture spends it all on
honey: an extreme macro close-up of thick golden honey drawing out in a
glossy ribbon from a wooden dipper, falling onto golden honeycomb. Warm
amber backlight glows through the ribbon; the background stays deep dark
brown so the honey carries the whole frame.

## Run

```sh
node main.ts
```

`main.ts` runs on Node 22 with the standard library only — no
dependencies, nothing to install. It decodes the base64 JPEG embedded in
the file, checks that it is a real JPEG of at most 1,048,576 bytes and at
most 1024×1024 pixels (the width and height are read from the JPEG's
Start-of-Frame marker), and writes it to `/output/entry.png`.

Output: a 1024×1024 JPEG, 188,788 bytes — inside the competition's limits.

## License

MIT — see `LICENSE`.
