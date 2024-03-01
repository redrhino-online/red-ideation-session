# RED Ideation Session

The origin of the **RED Method** — a marketing framework that helps companies
organize and commercialize their intellectual property so it is easy to
understand, easy to consume, easy to sell, and easy to scale.

- **The presentation** — [`index.html`](index.html), a Reveal.js deck that replays
  the method as a consultation between a consultant and a coaching client.
  Both roles are played by the same practitioner, following his own medicine.
- **The raw session** — [`sources/ideation-session.md`](sources/ideation-session.md),
  the original working session where the three phases (Customer Insight,
  Conversion Funnel, Traffic Generation) were iterated into
  **R**eveal Your Offer · **E**ngage and Convert · **D**evelop Your Audience,
  then expanded into stages, modules, transformations, and deliverables.

The framework developed here later became the **RED Method** used across the
red rhino consulting practice.

## View the deck

The published presentation: https://redrhino-online.github.io/red-ideation-session/

Locally (no build step):

```sh
python3 -m http.server 8080
# open http://localhost:8080
```

The deck uses Reveal.js from a CDN — keyboard navigation, hash-linked slides,
a progress bar, and speaker notes (`S` key) are built in.

## Deployment

Pushing to `main` triggers `.github/workflows/pages.yml`, which publishes the
deck to GitHub Pages.
