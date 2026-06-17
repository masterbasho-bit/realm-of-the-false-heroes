# The Realm of the False Heroes

A D&D 5e Level 9 interlude for *Tomb of Annihilation* — formatted for [The Homebrewery](https://homebrewery.naturalcrit.com) (V3 renderer, A4).

This repo doubles as the **image host** for the brew. GitHub serves files in a public repo as raw bytes, which is exactly what Homebrewery's `![](url)` syntax needs.

## Contents

- [`realm-of-the-false-heroes.homebrew.md`](realm-of-the-false-heroes.homebrew.md) — the Homebrewery source. Paste into a new V3 / A4 brew.
- [`images/`](images/) — artwork. Drop image files here.

## How the image URLs work

Any file you put in `images/` is reachable at:

```
https://raw.githubusercontent.com/masterbasho-bit/realm-of-the-false-heroes/main/images/<filename>
```

That raw URL is what goes inside the `![](...)` in the brew.

## Naming convention

If you name the generated art exactly as below, the image code can be wired into the brew with no further edits. Each row also shows the final raw URL.

| File | Goes where | Raw URL |
|:--|:--|:--|
| `cover.png` | Title page | `…/main/images/cover.png` |
| `01-throne-room.png` | Part 1 — The Departure | `…/main/images/01-throne-room.png` |
| `02-excel-hall.png` | Part 2 — Arrival at ExCeL | `…/main/images/02-excel-hall.png` |
| `03-vr-booth.png` | Part 4 — VR Horror Booth | `…/main/images/03-vr-booth.png` |
| `04-claw-machine.png` | Part 4 — Claw Machine | `…/main/images/04-claw-machine.png` |
| `05-debate-club.png` | Part 4 — Debate Club | `…/main/images/05-debate-club.png` |
| `06-scifi-corridor.png` | Part 5 — Zone 1 (Sci-Fi) | `…/main/images/06-scifi-corridor.png` |
| `07-retro-arcade.png` | Part 5 — Zone 2 (Arcade) | `…/main/images/07-retro-arcade.png` |
| `08-lore-stage.png` | Part 5 — Zone 3 (Live Stage) | `…/main/images/08-lore-stage.png` |
| `09-main-stage.png` | Part 6 — The Grand Finale | `…/main/images/09-main-stage.png` |

(The nine location prompts in Appendix C of the brew map 1:1 onto rows 01–09.)

## Adding images

**Via the web (easiest):** open the `images/` folder on GitHub → **Add file → Upload files** → drag art in → **Commit**.

**Via git:**

```bash
cd realm-of-the-false-heroes
cp ~/path/to/art/*.png images/
git add images/ && git commit -m "Add artwork" && git push
```

Raw links go live within a few seconds of the push.
