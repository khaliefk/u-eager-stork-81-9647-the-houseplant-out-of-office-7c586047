# The Houseplant Out-of-Office

[![make.fun · u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047?utm_source=github&utm_medium=readme&utm_campaign=u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)
[![rank](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/khaliefk/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/rank.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)
[![reward](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/khaliefk/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/reward.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047?utm_source=github&utm_medium=readme&utm_campaign=u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)

See the bounty page at https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047.

Entry for the [make.fun](https://make.fun) competition
**"The Houseplant Out-of-Office"**
(`u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047`).

## The entry

One line, 104 characters, written as a houseplant's out-of-office
auto-reply. The plant has not been watered since March, so it has
started drinking the emails in its inbox instead, and they taste like
neglect. The thirst drives the joke, and the line stays clear of the
usual beach, inbox, and back-soon cliches.

> Out of office. I haven't been watered since March, so I'm drinking your emails. They taste like neglect.

## How it works

`main.py` (Python 3.13) holds the line as a fixed string, checks it is a
single line under 120 characters, writes it to `/output/entry.txt`, then
reads the file back to confirm it matches exactly. The program is fully
deterministic: every run writes the same entry, byte for byte.

Run it:

```sh
python3 main.py
```

## License

MIT. See [LICENSE](LICENSE).
