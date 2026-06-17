# 🐳 Hungry Whale — Eat the Ocean

A 1-day HTML MVP of a **drag-the-whale, eat-and-grow** casual game with an ocean theme. Inspired by the **Black Hole - Eat Everything** (#1 in iOS Puzzle, 16K ratings) genre, themed for the **whale** niche — a blue-ocean segment Google Play searches return *zero* competitors for.

## Why this exists

- **Original hit:** *Black Hole - Eat Everything* by Leapjoy Games (iOS 4.7⭐ / 16K ratings, Android 4.1⭐ / 51.7K reviews / 1M+ downloads). The "hole-eats-things" genre is on fire (3 hole-emoji apps in iOS Top Free at the same time).
- **The catch:** "hole swallow" / "hole eat" on Google Play returns **20+** copycat apps — straight copy is a red ocean.
- **The wedge:** Search "**whale + eat**" / "**whale + hole + swallow**" / "**whale + eat + puzzle**" → **zero** themed competitors. Whale IP is high-value (Free Willy / Octonauts / Finding Nemo / Bluey-adjacent), ocean visuals have built-in chill/ASMR appeal, and the "blubbery thicc whale" visual is a natural fit for the eating-grows-bigger mechanic.

## How to play

- **Drag** 🐋 around the ocean (or tap-to-move by tapping empty water)
- **Eat** 🐟 🐠 🦐 (small fish = +1), 🪼 (jellyfish = +2, glowing bonus), 🪸 (coral = +1, stuck in place)
- **Avoid** 🚢 (boat), 🪢 (net), 🦈 (shark) — each hit costs a ❤️
- **Goal:** eat 10 food per level. Hearts reset between levels. Win when you clear the goal; lose when hearts hit 0.
- **Growth:** as you eat, your whale gets bigger — making it easier to reach food but also a slightly bigger target.

## Run

```bash
# Just open the file
open index.html

# Or serve locally
python3 -m http.server 8000
# → http://localhost:8000
```

## Tech

- **Single HTML file** — no build, no framework
- HTML5 Canvas 2D
- Vanilla JS (no deps)
- DPR-aware rendering
- Touch + mouse unified input
- ~17 KB, 100% offline

## What's next (Day 2+)

- [ ] ASO test: ship to GitHub Pages, buy "black hole puzzle" + "whale puzzle" keywords
- [ ] Level progression: more obstacle variety (squid, submarine)
- [ ] Sound: chomp + bubble pop (WebAudio)
- [ ] High score / time-attack mode
- [ ] Capacitor wrap → iOS / Android native

## License

MIT — fork and ship your own themed variant.
