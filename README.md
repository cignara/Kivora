# Kivora

> **Where Kids Love to Learn & Play**
> A child-safe, gamified, adaptive learning ecosystem for children aged **2–11** (Toddler through Grade 5).

---

## Quick Links

| Resource | Path | Purpose |
|---|---|---|
| **Master Specification** | [`Kivora_Master_Specification_v3.0.md`](./Kivora_Master_Specification_v3.0.md) | Single source of truth — start here |
| **Content Templates** | [`content/templates/`](./content/templates/) | Blank fill-in templates for every content type |
| **Sample Content** | [`content/samples/`](./content/samples/) | Approved reference examples per content type |
| **Kivi Illustrator Brief** | [`assets/kivi/ILLUSTRATOR-BRIEF.md`](./assets/kivi/ILLUSTRATOR-BRIEF.md) | Commission document for the Kivi fox character art |
| **Homepage** | [`index.html`](./index.html) | Production public website (Tailwind v3, no CDN) |
| **Archived specs** | [`docs/archive/`](./docs/archive/) | Superseded documents — do not use for active work |

---

## Platform at a Glance

| | |
|---|---|
| **Target audience** | Children aged 2–11 (Toddler → Grade 5) |
| **Mascot** | Kivi the Fox |
| **Phase 1 worlds** | Alphabet Island · Math Mountain · Story Cove · Creativity Kingdom |
| **Phase 2 worlds** | Science Safari · Music Meadow · Brain Game Galaxy · Life Skills Village · Coding City |
| **Tech stack** | Next.js + TypeScript + Tailwind CSS · NestJS · PostgreSQL · Firebase Auth · Stripe · Vercel |
| **Compliance** | COPPA · GDPR-K · FERPA · UK AADC · WCAG 2.1 AA/AAA |

---

## Phase 1 Content Targets (MVP Launch)

| Content Type | Target | Worlds |
|---|---|---|
| Activities | 300 | All 4 Phase 1 worlds |
| Games | 80 | Alphabet Island · Math Mountain · Brain Game Galaxy |
| Stories | 100 | Story Cove |
| Videos | 60 | All 4 worlds |
| Coloring Pages | 200 | Alphabet Island · Creativity Kingdom |
| Printables | 150 | Math Mountain · Alphabet Island |
| Quizzes | 80 | All 4 worlds |

---

## Content Production Workflow

All content follows this linear CMS workflow — no step can be skipped:

```
Draft → Review → Approved → Published → Archived
```

Use the templates in [`content/templates/`](./content/templates/) to create new items.
Every item must pass the [pre-publish quality checklist](./Kivora_Master_Specification_v3.0.md#95-pre-publish-quality-checklist) before moving to Review.

---

## File Naming Convention

| Content Type | Pattern | Example |
|---|---|---|
| Activity | `ACT-NNN-slug.md` | `ACT-001-counting-coconuts.md` |
| Story | `STR-NNN-slug.md` | `STR-001-kivi-magic-forest.md` |
| Quiz | `QZ-NNN-slug.md` | `QZ-001-number-knowledge.md` |
| Video | `VID-NNN-slug.md` | `VID-001-adding-numbers-brief.md` |
| Printable | `PRT-NNN-slug.md` | `PRT-001-alphabet-tracing.md` |
| Coloring | `CLR-NNN-slug.md` | `CLR-001-kivi-colouring-page.md` |

---

## Reward Values Quick Reference

| Difficulty | XP | Coins | Gems |
|---|---|---|---|
| Pre-Easy (Toddler/Sensory) | 5 | 3 | 0 |
| Easy | 10 | 5 | 0 |
| Intermediate | 20 | 10 | 0–1 |
| Advanced | 35 | 15 | 1–2 |
| Master | 50 | 25 | 2–3 |
| Perfect score bonus | +10 | +5 | — |

> Coins are **never reduced** for low scores. Every attempt earns the base Coin reward.

---

## Kivi Asset Status

| Asset ID | File | Status |
|---|---|---|
| KV-001 | `kivi-idle.svg` | 🔴 To commission |
| KV-002 | `kivi-wave.svg` | 🔴 To commission |
| KV-003 | `kivi-happy-jump.svg` | 🔴 To commission |
| KV-004 | `kivi-celebrate.svg` | 🔴 To commission |
| KV-005 | `kivi-think.svg` | 🔴 To commission |
| KV-006 | `kivi-oops.svg` | 🔴 To commission |
| KV-007 | `kivi-read.svg` | 🔴 To commission |
| KV-008 | `kivi-paint.svg` | 🔴 To commission |
| KV-009 | `kivi-run.svg` | 🔴 To commission |
| KV-010 | `kivi-sleep.svg` | 🔴 To commission |
| KV-011 | `kivi-sinhala.svg` | ⚪ Phase 2 |
| KV-012 | `kivi-trophy.svg` | 🔴 To commission |

See [`assets/kivi/ILLUSTRATOR-BRIEF.md`](./assets/kivi/ILLUSTRATOR-BRIEF.md) for the full commission document.

---

## Contributing

Before creating any content item:
1. Read the relevant section of [`Kivora_Master_Specification_v3.0.md`](./Kivora_Master_Specification_v3.0.md)
2. Use the correct blank template from [`content/templates/`](./content/templates/)
3. Study the approved sample in [`content/samples/`](./content/samples/)
4. Run the pre-publish checklist before submitting for Review
