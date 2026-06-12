# Kivi the Fox — Illustrator Commission Brief
### Kivora Learning Platform · Character Asset Package v1.0

---

## 1. Who Is Kivi?

Kivi is the official mascot, guide, and emotional anchor of the Kivora learning platform for children aged 2–11. Kivi is a friendly, curious, energetic fox — always present, always encouraging, **never scary, never pressuring**.

Kivi's four core personality pillars:

| Pillar | What it means visually |
|---|---|
| **Curious** | Wide eyes, alert ears, leaning-forward posture |
| **Encouraging** | Open paws, warm blush, smile always present |
| **Funny** | Expressive eyebrows, exaggerated reactions, silly poses |
| **Safe** | Soft rounded forms, no sharp angles, no intimidating scale |

---

## 2. Character Design Specification

### 2.1 Species & Body Type

- **Species**: Red fox — stylised, NOT photorealistic
- **Body type**: Small, rounded, slightly chubby. Soft toy proportions.
- **Head-to-body ratio**: Approximately 1:1.2 (large head relative to body — approachable, never intimidating)
- **Render size in-app**: 180–220px tall at default. Must read clearly at **48×48px minimum** (sidebar) and at **400×400px** (full-screen celebration overlay)

### 2.2 Colour Palette — Exact Values

| Body Region | Colour | Hex | Notes |
|---|---|---|---|
| Main fur | Warm orange | `#FF7B35` | Primary read — consistent across all 12 variants |
| Belly / muzzle / inner ears | Cream | `#FFF3E0` | |
| Ear tips / tail tip | White | `#FFFFFF` | |
| Eyes — iris/pupil | Deep brown, large, round | `#4A2C10` | With white catchlight dot |
| Nose | Small, rounded, dark brown | `#3E1F08` | |
| Happy-state cheeks | Soft blush circles | `#FFB3A0` at 60% opacity | Present in positive-emotion variants only |

### 2.3 Anatomy Details

**Eyes**
- Large, expressive, anime-adjacent — NOT hyper-realistic
- Eyes are the **primary emotion carrier** — all emotional states read first in the eyes
- No eyelashes that read as gendered — Kivi is gender-neutral
- Always two white catchlight dots (top-left of each eye)

**Ears**
- Large, upright, slightly rounded tips — fox-like but softened
- Inner ear: cream (`#FFF3E0`)
- Ear tips: white (`#FFFFFF`)

**Tail**
- Fluffy, full, always visible and expressive
- Tip always white
- Tail communicates emotion: wagging = excited, still = curious, tucked = gentle/sleepy
- The tail must be visible in every variant unless the pose physically prevents it

**Paws/Hands**
- Small, rounded, 3-finger paws
- Capable of holding props (book, paintbrush, trophy) or waving
- No claws visible — always soft and rounded

---

## 3. Style Directives — Non-Negotiable

| Rule | Detail |
|---|---|
| **Vector only** | All 12 assets must be clean SVG. No raster elements inside Kivi's core forms. |
| **Stroke weight** | Consistent **2px** stroke weight across all variants. Fill-dominant, not line-dominant. |
| **Outline rule** | No dark outlines on fur colour transitions — use **colour value shifts only**. Hard black outlines on eye pupils and nose ONLY. |
| **Gradient limit** | Maximum 2-stop gradients only. Keep visually simple. |
| **Consistency** | Kivi's base body shape, proportions, and exact colour values must be **pixel-identical** across all 12 variants. Only the expression, posture, and held props change. |
| **Layer naming** | SVG must be single-layer with grouped paths by body region: `#kivi-body`, `#kivi-tail`, `#kivi-face`, `#kivi-hands`, `#kivi-expression`. This is required for per-group CSS animation targeting. |

---

## 4. The 12 Asset Library

Deliver all 12 as individual SVG files. File names are fixed — do not rename.

| Asset ID | File Name | Pose / Expression | Key Visual Detail | Animation (developer-applied) |
|---|---|---|---|---|
| KV-001 | `kivi-idle.svg` | Standing, neutral-happy, arms relaxed at sides | Default dashboard presence. Subtle curiosity in eyes. | Float loop: `translateY(0→-12px)` 3s |
| KV-002 | `kivi-wave.svg` | One arm raised mid-wave, big smile, eyes crinkled | Welcome / onboarding / first login | Wave arm 2-cycle 1.5s |
| KV-003 | `kivi-happy-jump.svg` | Mid-jump, arms raised, mouth open in big smile | Correct answer / activity finish | Scale burst + jump 0.5s |
| KV-004 | `kivi-celebrate.svg` | Full celebration pose — confetti optional, trophy in paw or arms wide | Badge earned / level-up / certificate | Shimmer + wiggle (full overlay) |
| KV-005 | `kivi-think.svg` | One paw on chin, eyes looking up-left, tail still | Hint delivery / quiz intro / loading | Tail flick 2s loop |
| KV-006 | `kivi-oops.svg` | Slightly startled, not sad — hands up in "oops" gesture, small wince | Wrong answer / retry prompt. **Must read as friendly, NOT punishing.** | Head-shake 0.4s |
| KV-007 | `kivi-read.svg` | Sitting, holding open book, eyes looking at pages | Story Cove / Read section | Page-turn motion 2s loop |
| KV-008 | `kivi-paint.svg` | Standing, paintbrush in paw raised, slight lean | Creativity Kingdom / Colouring Hub | Brush stroke 1.5s loop |
| KV-009 | `kivi-run.svg` | Mid-run, leaning forward, ears back in wind | World transitions / loading between screens | Run cycle 0.6s loop |
| KV-010 | `kivi-sleep.svg` | Curled or sitting, eyes closed, breathing gently, ZZZ optional | Session timeout / bedtime lock. **Must be gentle and comforting — never alarming.** | Breathing motion 4s loop |
| KV-011 | `kivi-sinhala.svg` | *(Phase 2 only — reserved)* | TBD. Cultural context brief to follow. | TBD |
| KV-012 | `kivi-trophy.svg` | Holding golden trophy above head, huge smile, confetti | Certificate award / World mastery | Gold shimmer pulse 1s loop |

### Priority Order for Delivery

Phase 1 requires these 6 first (before any content goes into testing):

1. **KV-001** (idle) — used on every loading state and dashboard
2. **KV-002** (wave) — homepage hero and first login
3. **KV-003** (happy-jump) — every correct answer
4. **KV-006** (oops) — every wrong answer
5. **KV-005** (think) — hints and quiz intros
6. **KV-009** (run) — loading transitions

Remaining 6 (KV-004, KV-007, KV-008, KV-010, KV-012) to follow before launch. KV-011 is Phase 2.

---

## 5. Expressions Reference (for KV-001 through KV-012)

| Emotion | Eyes | Mouth | Ears | Tail | Cheek blush |
|---|---|---|---|---|---|
| Happy (default) | Round, slight crinkle | Soft smile | Upright | Gently wagging | Subtle |
| Very happy (celebrate) | Crinkled, stars optional | Big open smile | Perked forward | Vigorous wag | Strong |
| Thinking | Looking up-left | Neutral/slight purse | One slightly tilted | Still | None |
| Oops (friendly) | Wide, slightly raised brow | Small "oh!" open | Back slightly | Tucked slightly | None |
| Sleepy | Closed or heavy-lidded | Neutral, relaxed | Drooped | Still, curled | None |
| Reading | Focused, tracking text | Neutral, engaged | Upright | Still | None |
| Running | Squinted (wind) | Determined smile | Flat back | Streaming behind | None |

---

## 6. What NOT to Design

| Do not include | Why |
|---|---|
| Aggressive or scary expressions | Child safety — even mild fear reads badly for ages 2–5 |
| Visible claws | Makes Kivi read as a threat |
| Tears or crying | No negative consequence framing — Kivi is never sad, only gentle |
| Countdown timers in any asset | Spec prohibition on time pressure mechanics |
| Any brand references, logos, or text in the character | Clean assets for animation and future localisation |
| Highly detailed backgrounds within the character SVG | Kivi is always composited onto world-specific backgrounds separately |

---

## 7. Deliverables & File Specifications

| Spec | Requirement |
|---|---|
| File format | SVG (scalable vector — no embedded rasters) |
| Viewport | `viewBox="0 0 400 400"` for all 12 assets |
| Colour mode | RGB, hex values as specified in Section 2.2 |
| Layer structure | Grouped as `#kivi-body`, `#kivi-tail`, `#kivi-face`, `#kivi-hands`, `#kivi-expression` |
| File naming | Exact filenames from Section 4 column "File Name" — no variations |
| Source files | Provide original editable source (Illustrator .ai or Figma .fig) alongside SVG export |
| Phase 1 priority | KV-001, KV-002, KV-003, KV-005, KV-006, KV-009 first |
| Phase 1 deadline | [Insert date] |
| Full delivery | [Insert date] |

---

## 8. Consistency Test

Before final delivery, confirm:
- [ ] Place all 12 SVGs side by side at 200×200px — Kivi's fur colour, ear shape, nose, and eye size must be identical across all variants
- [ ] Scale KV-001 down to 48×48px — Kivi must still read as a recognisable fox, not an orange blob
- [ ] Scale KV-004 up to 600×600px — no pixelation, no artifacts
- [ ] Verify SVG layer names match the required group IDs

---

## 9. Contact

Brief prepared by: Kivora Content Team
Specification reference: `Kivora_Master_Specification_v3.0.md`, Section 2

Questions: [insert contact email]
