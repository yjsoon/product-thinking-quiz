# Product Thinking Quiz

A small static site built from the Institute of Digital Government's
[Product Thinking learning pathway](https://www.idg.gov.sg/product-thinking/) (modules 1–7):
an intro page, a quiz, and a game that teaches the same habits by making you fly through them.

Live: **https://yjsoon.github.io/product-thinking-quiz/**

| File | What it is |
| --- | --- |
| `index.html` | Title-and-tagline intro page |
| `quiz.html` | 16-question quiz with per-answer explanations, scoring and review |
| `game.html` | *Flappy Product* — a side-scroller where every gate is a product decision |

## The quiz

Sixteen multiple-choice questions covering every module:

- **Understanding the problem** — why projects fail, solving one core problem first, Policy-Ops-Tech
- **Craft a clear problem statement** — the 4Cs: Clarity, Consequence, Cause, Confirmation
- **Start with the whys** — Five Whys, and choosing a root cause you can actually act on
- **Metrics** — outputs vs outcomes, leading and lagging indicators, SMART, Value-Cost Ratio
- **Assumptions and risks** — market/technical/team risk, the four de-risking stages
- **A good customer experience** — why compulsory services need it most, the 11-star framework
- **Key takeaways** — the three mindset shifts

Answer with a click or the `1`–`4` / `A`–`D` keys; `Enter` moves on.

## The game

*Flappy Product* turns the pathway into thirteen gates. Each wall has **two** openings —
one is the product-thinking move ("Ask why five times", "12 days to 3 days", "FormSG + a sheet"),
the other is the shortcut that feels faster ("Patch the symptom", "Shipped 4 features",
"Build the full system"). They are drawn identically, so the label is the only tell.

- Space, click or tap to flap
- Through the right opening: a gate cleared, and the principle behind it
- Through the wrong one: a budget dot, and the reason it costs you
- Hit the wall between them and you pay the same — not deciding is a decision
- Three budget dots, thirteen gates, and the run gets faster as you go

Gates are shuffled each run, and which opening is correct flips at random.

## Running it

No build step, no dependencies. Open `index.html` in a browser, or serve the folder:

```sh
python -m http.server
```

Fonts (Fraunces and IBM Plex Mono) load from Google Fonts, so the intended typography needs a
network connection; it falls back to Georgia and a system mono otherwise. All three pages follow
the viewer's light or dark theme.

## Credit

Content is derived from the IDG Product Thinking pathway. The frameworks, examples and phrasing
belong to the Institute of Digital Government, GovTech Singapore.
