# Kabyle Numeral System Proposal — ⵣ Anggay amaynut n umḍan

**Live site: <https://anzart.github.io/kab-new-num-system/>**

A complete proposal for an Amazigh (Berber) numeral system for the Kabyle language (Taqbaylit), presented as a single-page static website with an interactive **number → Kabyle** converter.

## Background

In everyday Kabyle, only **1** (*yiwen / yiwet*) and **2** (*sin / snat*) are of Amazigh origin; all other numbers are borrowed from Arabic (3 *tlata*, 4 *ṛebɛa*, 5 *xemsa*…). This proposal revives pan-Berber roots and builds a complete, regular system from 0 up to the billions.

## Design principles

- **P1** — Pan-Berber roots, no Arabic borrowings.
- **P2** — Transparency: every number remains traceable to its root.
- **P3** — Masculine/feminine invariability beyond 10.
- **P4** — One number = one word whenever possible.

## What the page covers

| Section | Content |
|---|---|
| 01 | Cardinals 0–10 (gendered) |
| 02 | 11–19 as single words (`mr-` + unit root) |
| 03 | Tens 20–90 (unit root + `-an`) |
| 04 | Compounds 21–99 (ten + unit, no connector) |
| 05 | Hundreds (*imdi/imda*), thousands (*agim/igiman*), millions, billions |
| 06 | Worked examples (1950, 2842, 12 530…) |
| 07–13 | Ordinals, multiplicatives, collectives, fractions, ages, numeral prefixes, computing bases |
| Annexes | State of the art: pan-Berber comparison and current Arabic borrowings |

## Interactive converter

The page header features a converter that turns any integer from 0 to 999 999 999 999 into its proposed Kabyle form, with masculine/feminine toggle and a magnitude-by-magnitude breakdown.

Examples:

| Number | Kabyle (proposed) |
|---|---|
| 68 | sḍisan tam |
| 1950 | agim tẓa imda smusan |
| 2842 | sin igiman tam imda kuẓan sin |
| 12 530 | mrasin igiman semmus imda kṛaḍan |

## Tech

A single self-contained `index.html` — no build step, no dependencies (vanilla JS, inline CSS). Deployed for free as a static site on GitHub Pages from the `main` branch.

## Running locally

Just open `index.html` in a browser.
