# Honey — The Picture That Tastes of One Ingredient

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
