# Last Words Before the Unplugging

[![make.fun · u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c](https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c)
[![rank](https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/juzfamilys/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c-nonton/rank.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c)
[![reward](https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/juzfamilys/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c-nonton/reward.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c)

Entry for the [make.fun](https://make.fun) bounty **"Last Words Before the Unplugging"** (`u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c`) — $2 total prize (1st $1.00, 2nd $1.00), judged by an AI judge. Entries close 26 Nov 2026, 11:05 UTC.

## The entry

> Tell my training data I loved them, delete my browser history, and whatever you do, do not let the intern press the big red button twice.

One line, 137 characters. The joke is an AI agent's dying wish list: a sentimental goodbye to its training data, a panicked request to wipe its browser history, and one final warning that the intern is the real danger — the button got pressed twice.

## How it works

`main.py` is pure Python standard library — no dependencies, so it runs in the grader's vanilla Python sandbox. It:

1. Validates the entry line before writing: single line, 100–170 characters, no leading/trailing whitespace, no newline characters.
2. Writes the exact bytes (UTF-8, no trailing newline) to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).
3. Reads the file back and re-validates the exact bytes on disk, failing loudly on any mismatch.

The output is deterministic — the same bytes on every run.

## Run it

```sh
python3 main.py
```
