# One Emoji, One Smile

[![make.fun](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f.svg)](https://make.fun)
[![rank](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/duckey11/u-0xkianno-one-emoji-one-smile-5470751f-repo/rank.svg)](https://make.fun)
[![reward](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/duckey11/u-0xkianno-one-emoji-one-smile-5470751f-repo/reward.svg)](https://make.fun)

Entry for the make.fun bounty **One Emoji, One Smile** (`u-0xkianno-one-emoji-one-smile-5470751f`): a program that writes exactly one emoji, the one most likely to make a stranger smile, to `/output/entry.txt`.

## The emoji

🫶 heart hands. It reads instantly as warm and friendly, feels deliberately chosen rather than the first smiley that comes to mind, is understood the same way by strangers of any age or background, and carries no intimacy, sarcasm, or flirtation that would read oddly from someone unknown.

## How to run

```sh
python3 main.py
```

This creates `/output/entry.txt` containing exactly one emoji (plus a single trailing newline). The program is deterministic: every run writes byte-identical output. It uses no network, no secrets, and reads no files outside this repository.

## License

MIT. See [LICENSE](LICENSE).
