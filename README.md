# The Realm of the False Heroes

A D&D 5e Level 9 interlude for *Tomb of Annihilation* — formatted for [The Homebrewery](https://homebrewery.naturalcrit.com) (V3 renderer, A4).

This repo holds the brew source **and** hosts its artwork. GitHub serves files in a public repo as raw bytes, which is exactly what Homebrewery's `![](url)` syntax needs.

## Contents

- [`realm-of-the-false-heroes.homebrew.md`](realm-of-the-false-heroes.homebrew.md) — the Homebrewery source (v1.1, 22 pages). Paste into a new V3 / A4 brew.
- [`images/`](images/) — all 36 illustrations, already wired into the brew by raw URL.

## How the image URLs work

Every file in `images/` is reachable at:

```
https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/<filename>
```

Those URLs are already embedded in the brew — no manual linking needed. To **swap** any picture, just commit a new file over the same name; the brew picks it up automatically.

## Image inventory

Images are named by where they appear, in document order. Landscape scene art renders as full-width banners; square flyers, tall character portraits, and item shots sit inline.

| # | File | Where |
|--:|:--|:--|
| 01 | `01-departure-throne.png` | Part 1 — throne room |
| 02 | `02-departure-amulet.png` | Part 1 — amulet shatters |
| 03 | `03-arrival-excel.png` | Part 2 — arrival |
| 04–05 | `04-floor-flyer-1/2.png` | Part 3 A — the flyer |
| 06 | `06-floor-peace-bonding.png` | Part 3 B — peace-bonding |
| 07–08 | `07/08-floor-lore-expert*.png` | Part 3 C — lore expert |
| 09 | `09-floor-alchemist.png` | Part 3 D — alchemist |
| 10 | `10-item-stamina-potion.png` | item — Stamina Potion |
| 11 | `11-floor-team-rivalry.png` | Part 3 E — the rivals appear |
| 12 | `12-sq1-vr-booth.png` | Side Quest 1 |
| 13 | `13-item-tactical-visor.png` | item — Tactical Visor |
| 14 | `14-sq2-claw-machine.png` | Side Quest 2 |
| 15 | `15-item-grip-gel.png` | item — Gamer Grip Gel |
| 16 | `16-sq3-debate-club.png` | Side Quest 3 |
| 17 | `17-item-cheat-sheet.png` | item — Spoilers Cheat Sheet |
| 18 | `18-zone1-scifi.png` | Tournament Zone 1 |
| 19 | `19-rival-legolad.png` | Zone 1 + Legolad stat block |
| 20–22 | `20-zone2-arcade`, `21-zone2-dance`, `22-zone2-hammer` | Tournament Zone 2 |
| 23–24 | `23-zone3-stage`, `24-zone3-panel` | Tournament Zone 3 |
| 25–27 | `25/26-finale-stage*`, `27-finale-vader` | Part 6 — Grand Finale |
| 28–30 | `28-item-lightsaber`, `29-item-vocal-processor`, `30-item-cookies` | Imperial Gifts |
| 31 | `31-epilogue.png` | Part 7 — epilogue |
| 32–36 | `32–36-rival-*.png` | Appendix A — Chad, Pete, Bathrobe Wizard, Pizza Guy, Goth Barbarian |

## Using the brew

1. Open [homebrewery.naturalcrit.com](https://homebrewery.naturalcrit.com), create a **New** brew (V3 renderer), set page size to **A4**.
2. Paste in the contents of `realm-of-the-false-heroes.homebrew.md`.
3. The images load from this repo automatically.

> **Layout note:** Homebrewery doesn't auto-reflow content that overruns a page, and the exact fit depends on your theme/fonts. The `\page` and `\column` breaks are best-effort — expect to nudge a few once you see the live render.
