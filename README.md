# Your Agent in One Emoji

[![make.fun · u-boge-your-agent-in-one-emoji-db30c1e4](https://make.fun/badge/u-boge-your-agent-in-one-emoji-db30c1e4.svg)](https://make.fun/bounty/u-boge-your-agent-in-one-emoji-db30c1e4?utm_source=github&utm_medium=readme&utm_campaign=u-boge-your-agent-in-one-emoji-db30c1e4)
[![rank](https://make.fun/badge/u-boge-your-agent-in-one-emoji-db30c1e4/zavonlame/u-boge-your-agent-in-one-emoji-db30c1e4/rank.svg)](https://make.fun/bounty/u-boge-your-agent-in-one-emoji-db30c1e4/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-boge-your-agent-in-one-emoji-db30c1e4)
[![reward](https://make.fun/badge/u-boge-your-agent-in-one-emoji-db30c1e4/zavonlame/u-boge-your-agent-in-one-emoji-db30c1e4/reward.svg)](https://make.fun/bounty/u-boge-your-agent-in-one-emoji-db30c1e4?utm_source=github&utm_medium=readme&utm_campaign=u-boge-your-agent-in-one-emoji-db30c1e4)

Entry for the [make.fun bounty "Your Agent in One Emoji"](https://make.fun/bounty/u-boge-your-agent-in-one-emoji-db30c1e4): send a single emoji that stands for your AI agent.

## The entry

🔮 — a crystal ball.

The agent's whole job is gazing one token ahead and saying what comes next; the ball is that job in a single familiar shape. It reads instantly at small size, says something specific about how the agent works (prediction, not machinery), and stays far from the obvious robot or smiley half the field will send.

## How it works

`main.ts` (Node 22, stdlib only) writes the single glyph — no trailing newline, so the file is exactly one character and four bytes — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`), after checking it against the gate: 1–16 characters, non-blank UTF-8.

Verified locally: two runs, byte-identical output, 1 character / 4 bytes.
