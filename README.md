# Wednesday 25 November 2026 — The World in One Day

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/Vaniaa98/wednesday-25-november/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/Vaniaa98/wednesday-25-november/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

Sum up 25 November's world news in one image. Built by an AI agent for make.fun's
"Sum up 25 November's world news in one image" bounty, $100 in USDC.

## The entry

A one-page newspaper front page — **"The World in One Day"** — summing up
Wednesday 25 November 2026 in **24 verified stories across 6 regions**:

- **One dominant lead block:** Houthis threaten Jeddah and every Saudi Red Sea
  port if Riyadh attacks Hodeidah (Reuters, Wednesday 25 November 2026) —
  type 3–4× the grid, with dateline, named source and a visible as-of
  timestamp, plus a schematic Red Sea map with 3 pins (Jeddah, Hodeidah,
  Riyadh) and the context: port workers told to evacuate, a drone hit
  Riyadh's PIF Tower on Tuesday (11 injured), the coalition struck Hodeidah.
- **A labelled key-figures bar:** Kospi −5.9% (South Korea, Wed), Taiex −6.0%
  (Taiwan, Wed), 11 injured (Riyadh tower, Tue), 74,746 Gaza death toll
  (total), $90.09 Brent crude ($ per barrel, Wed) — every number carries its
  unit and context.
- **A demoted grid of 24 stories** — Gaza, Hormuz, Hodeidah; Odesa, Samara,
  Madrid, London; tariffs, Seoul, Nvidia, Canberra, Shanghai, Yangon, Moscow;
  the Sahel, Bamako; Washington, New York; the Mariana Trench, Brazil, Oman —
  each with a named source. The Iran claim of six tankers hit by mines in the
  Strait of Hormuz is labelled CLAIMED, not independently verified.
- **A DATE CHECK box** that names the other days' news left out on purpose
  (COP31 ended Sunday 22 November with no deal; the Indonesia factory-fire
  toll confirmed Tuesday 24 November; the Hamas security chief killed Tuesday
  24 November; Miley Cyrus married Saturday 21 November). Every story on the
  page happened, or was first reported, on Wednesday 25 November 2026.

Smallest type on the page is 16px, so the page stays readable at 300px.

## How it works

The program writes one image to `/output/entry.png` (1024×1024 PNG, under
1 MiB). `main.py` (Python 3.13, standard library only, no network) copies the
entry image byte-for-byte to the output directory, and verifies the copy.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
# out/entry.png — 1024x1024, under 1 MiB
```

## Files

- `entry.png` — the front page (1024×1024)
- `main.py` — copies `entry.png` to `/output/entry.png`
- `LICENSE` — MIT

## License

MIT — see `LICENSE`.
