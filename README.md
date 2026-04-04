# Meadow Gold × UH Warriors - Collect

A web prototype built for the **Innovate808 Business Competition**. It's a digital collectible card experience that partners Meadow Gold (Hawaii's local dairy brand) with UH Warriors athletics.

## Concept

Customers find a unique 6-digit code under their Meadow Gold gallon cap, enter it on this web app, and unlock a digital trading card — either a UH athlete card or a special prize card. Cards can be saved to a personal collection.

## How It Works

1. **Landing** — Introduces the promotion with a "Scan. Sip. Collect." hook.
2. **Quiz** — Collects short consumer survey data (household size, age group, product preferences) before revealing a card.
3. **Code Entry** — User types the 6-digit code found inside their cap.
4. **Reveal** — An animated card flip reveals the unlocked card (athlete or prize).
5. **Collection** — Users log in to save cards and track collection progress across all 8 cards.

## Cards

### Athlete Cards (6)

| Code   | Athlete            | Sport               | Rarity  |
|--------|--------------------|---------------------|---------|
| 836275 | Karol Ostrowski    | Men's Swim Team     | Rare    |
| 274819 | Holly N.           | Women's Swim Team   | Epic    |
| 519302 | Warrior #3         | Football            | Rare    |
| 748201 | Warrior #4         | Baseball            | Common  |
| 930174 | Warrior #5         | Women's Basketball  | Common  |
| 612847 | Warrior #6         | Soccer              | Rare    |

### Prize Cards (2)

| Code   | Prize                    | Rarity    |
|--------|--------------------------|-----------|
| 000001 | Lani Moo Farm Experience | Legendary |
| 000002 | UH Game Day VIP          | Epic      |

## Tech Stack

- **React 18** (via CDN UMD build) with Babel standalone — no build step required
- **Single HTML file** — fully self-contained, open directly in a browser
- **Supabase Storage** — athlete and prize card photos served from a public bucket
- Card flip animation in pure CSS (`perspective`, `rotateY`, `backface-visibility`)

## Running Locally

No install or build needed. Just open `index.html` in a browser:

```bash
open index.html
```

Or serve it with any static file server:

```bash
npx serve .
```

## Project Context

This prototype was created for the **Innovate808** business competition in Hawaii. The concept ties Meadow Gold's existing gallon jug product line to UH Warriors athletics through a gamified digital collectible mechanic — driving brand engagement, repeat purchases, and fan community participation.
