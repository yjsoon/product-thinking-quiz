# Product Thinking Quiz

A small static site: a one-page introduction to product thinking, and a 16-question
quiz built from the Institute of Digital Government's
[Product Thinking learning pathway](https://www.idg.gov.sg/product-thinking/) (modules 1–7).

| File | What it is |
| --- | --- |
| `index.html` | Title-and-tagline intro page, linking to the quiz |
| `quiz.html` | The quiz — questions, answer checking, scoring and review |

## The quiz

Sixteen multiple-choice questions covering every module of the pathway:

- **Understanding the problem** — why projects fail, solving one core problem first, the Policy-Ops-Tech mindset
- **Craft a clear problem statement** — the 4Cs: Clarity, Consequence, Cause, Confirmation
- **Start with the whys** — Five Whys, and choosing a root cause you can actually act on
- **Metrics** — outputs vs outcomes, leading and lagging indicators, SMART, Value-Cost Ratio
- **Assumptions and risks** — market/technical/team risk, and the four de-risking stages
- **A good customer experience** — why compulsory services need it most, the 11-star framework
- **Key takeaways** — the three mindset shifts

Answer with a click or the `1`–`4` / `A`–`D` keys; `Enter` moves on. Every answer is
explained against the source material, and the end screen scores you with a full review.

## Running it

No build step, no dependencies. Open `index.html` in a browser, or serve the folder:

```sh
python -m http.server
```

Fonts (Fraunces and IBM Plex Mono) load from Google Fonts, so the intended typography
needs a network connection; it falls back to Georgia and a system mono otherwise.
The pages follow the viewer's light or dark theme.

## Credit

Quiz content is derived from the IDG Product Thinking pathway. The frameworks,
examples and phrasing belong to the Institute of Digital Government, GovTech Singapore.
