# Swissy Tees 🏔️🐕

**Premium apparel for people who love Swiss Mountain Dogs.**
*Big dogs. Bigger hearts.*

Swissy Tees is a small apparel company owned and run by **Declan**, a 10-year-old
entrepreneur from **Evergreen, Colorado**, alongside his Swissy, **Heinz**. We make
soft, well-made tees and merch that celebrate the gentle giants of the Alps — the
four Swiss Mountain Dog breeds (Bernese, Greater Swiss, Appenzeller, and Entlebucher).

🌐 **Website:** [swissytees.com](https://swissytees.com)

---

## What's in this repo

| File | Purpose |
|------|---------|
| `index.html` | The "Launching Soon" landing page (single-file, no dependencies) |
| `logo.png` | Brand badge logo — **add this file** (used by the landing page + favicon) |
| `Swissytees-Brand-Foundation.md` | Brand strategy: positioning, voice, palette, product ideas |
| `.gitignore` | Standard ignores |

> **Note:** Save the brand logo image into this folder as `logo.png`. The landing
> page shows a fallback ring until it's present.

---

## Brand colors

| Role | Hex |
|------|-----|
| Badge Navy | `#1f2a44` |
| Swiss Red | `#cf4a4f` |
| Rust / Tan | `#c47a3c` |
| Cream | `#f5f0e6` |
| White | `#ffffff` |

---

## Running locally

It's a static page — just open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Collecting email signups

The signup form works client-side out of the box. To store real addresses, set
`FORM_ENDPOINT` near the bottom of `index.html` to a free
[Formspree](https://formspree.io) or Mailchimp form URL.

---

*© 2026 Swissy Tees · Mountain Apparel · Made with love (and a little dog hair)*
