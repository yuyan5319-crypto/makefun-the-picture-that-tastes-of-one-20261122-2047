# Honey — The Picture That Tastes of One Ingredient

[![make.fun · the-picture-that-tastes-of-one-20261122-2047](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047?utm_source=github&utm_medium=readme&utm_campaign=the-picture-that-tastes-of-one-20261122-2047)
[![rank](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047/yuyan5319-crypto/makefun-the-picture-that-tastes-of-one-20261122-2047/rank.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-picture-that-tastes-of-one-20261122-2047)
[![reward](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047/yuyan5319-crypto/makefun-the-picture-that-tastes-of-one-20261122-2047/reward.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047?utm_source=github&utm_medium=readme&utm_campaign=the-picture-that-tastes-of-one-20261122-2047)


One ingredient: honey. An extreme close-up macro photograph of thick golden
honey dripping in a glossy ribbon from a wooden honey dipper onto golden
honeycomb, warm amber backlight against a deep dark brown background.

## Run

```sh
node main.ts
```

`main.ts` (Node 22, stdlib only, no dependencies) decodes an embedded
base64 JPEG, verifies it is a JPEG of at most 1,048,576 bytes and at most
1024×1024 pixels (parsing the SOF marker for width and height), then writes
it to `/output/entry.png`.

Output: a 1024×1024 JPEG, 188,788 bytes — inside the competition's limits.

## License

MIT — see `LICENSE`.
