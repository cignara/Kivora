---
# ACTIVITY METADATA — fill every field before submitting for Review
id:               ""                  # ACT-NNN  (assigned by content lead)
title:            ""                  # Fun, world-themed. Max 8 words. Not a DB label.
type:             activity
subject:          ""                  # literacy | math | science | coding | life-skills | creativity | music
world:            ""                  # alphabet-island | math-mountain | story-cove | creativity-kingdom | ...
ageGroup:         ""                  # toddler | pre-k | kindergarten | grade-1 | grade-2 | grade-3 | grade-4 | grade-5
grade:            ""                  # Display label e.g. "Pre-K" or "Grade 2"
difficulty:       ""                  # pre-easy | easy | intermediate | advanced | master
duration:         0                   # Estimated minutes (integer). Must be ≤ 10.
theme:            ""                  # Slug of visual/curriculum theme e.g. "tropical-beach"
skills:           []                  # 1–3 skill slugs e.g. ["counting", "number-recognition"]
learningObjective: ""                 # EXACTLY ONE string. Starts with a verb. e.g. "Count objects 1–10"
rewardPoints:     0                   # Easy=10 | Int=20 | Adv=35 | Master=50
gemReward:        0                   # 0=none | 1=standard | 2=challenge | 3=mastery only
coinReward:       0                   # Easy=5 | Int=10 | Adv=15 | Master=25  (+5 bonus for perfect score)
kiviAsset:        ""                  # KV-001 through KV-012
audioRequired:    true                # Always true unless explicitly approved otherwise
speakLoad:        ""                  # REQUIRED — Kivi reads this when the activity/question loads. Full sentence, child-facing.
speakOk:          ""                  # REQUIRED — Kivi says this on correct answer. Must reinforce the learning, not just celebrate.
speakNo:          ""                  # REQUIRED — Kivi explains this on wrong answer. Must COUNT/DEMONSTRATE the correct answer. Never just "Try again!"
accessibilityFlags: []                # e.g. ["large-targets", "audio-first", "adhd-short-segments"]
offlineAvailable: false               # Set to true only after download confirmed in CMS
status:           draft               # draft | review | approved | published | archived
createdBy:        ""
reviewedBy:       ""
lastUpdated:      ""                  # ISO date YYYY-MM-DD
---

# [TITLE]

## Phase 1 — Hook (30 seconds)

> **Kivi says** (speech bubble, max 12 words, Grade 1–2 reading level):
> "[Write Kivi's intro line here]"

**Scene description** (what the child sees on screen):
[Describe the opening animated scene — what world are we in? What's happening? Keep it vivid and specific. 2–4 sentences.]

**Audio narration script**:
[Full read-aloud script for this phase. This is everything Kivi/narrator says.]

---

## Phase 2 — Warm-Up (2 minutes, 2 interactions, score NOT recorded)

> **Kivi says**: "[Warm-up intro line — max 12 words]"

### Warm-Up Interaction 1

**Type**: [tap-to-select | drag-and-drop | matching | trace | sequence]
**Prompt**: [Exact question or instruction shown to child]
**Visual**: [Describe what's on screen]
**Correct response**: [What the correct answer is]
**Kivi on correct**: "[Kivi encouragement line — warm-up specific, max 12 words]"
**Kivi on wrong**: "[Gentle re-attempt line — no score, no penalty]"

### Warm-Up Interaction 2

**Type**: 
**Prompt**: 
**Visual**: 
**Correct response**: 
**Kivi on correct**: 
**Kivi on wrong**: 

---

## Phase 3 — Core Learning (8 minutes, 10 interactions)

> **Kivi says**: "[Transition into core — max 12 words]"

> ⚠️ **Rule**: Hint appears on the **2nd** wrong attempt only — never the 1st, never withheld indefinitely.
> ⚠️ **Rule**: No score is displayed during this phase.

### Interaction 1

**Type**: [tap-to-select | drag-and-drop | matching | sequence | fill-in-blank | audio-match]
**Difficulty tier**: [same as activity difficulty]
**Prompt**: 
**Visual**: 
**Options** (if multiple choice — list all, mark correct with ✓):
- [ ] Option A
- [ ] Option B
- [✓] Option C
- [ ] Option D

**Correct response**: 
**Kivi on correct** (KV-003): "[Celebration line — max 12 words]"
**Kivi on 1st wrong** (KV-006): "[Gentle nudge — max 12 words. Do NOT reveal answer.]"
**Hint on 2nd wrong** (KV-005): "[Hint that guides without revealing — max 15 words]"

---

### Interaction 2

**Type**: 
**Prompt**: 
**Visual**: 
**Options**:
-
-
-
-
**Correct response**: 
**Kivi on correct**: 
**Kivi on 1st wrong**: 
**Hint on 2nd wrong**: 

---

### Interaction 3
[repeat structure above]

### Interaction 4
[repeat structure above]

### Interaction 5
[repeat structure above]

### Interaction 6
[repeat structure above]

### Interaction 7
[repeat structure above]

### Interaction 8
[repeat structure above]

### Interaction 9
[repeat structure above]

### Interaction 10
[repeat structure above]

---

## Phase 4 — Wrap-Up (60 seconds)

**XP earned**: [value from metadata `rewardPoints` + any perfect-score bonus]
**Coins earned**: [value from metadata `coinReward`]
**Gems earned**: [value from metadata `gemReward`]
**Kivi asset shown**: [Asset ID e.g. KV-004 for celebration]

> **Kivi says** (KV-004 — celebrate): "[Big celebration line — max 12 words, personalise with child name if available]"

**Summary screen content**:
- What did we learn today? [One sentence, child-facing language]
- Stars earned: [rewardPoints]
- Next activity suggestion: [slug of recommended next activity]

**Parent report auto-generated fields**:
- Subject: [from metadata]
- Skill practised: [from skills array]
- Duration: [from metadata]
- Learning objective: [from metadata]

---

## Accessibility Notes

| Profile | Specific accommodation for this activity |
|---|---|
| Toddler | [e.g. "All interactions tap-only. No drag. 64px targets."] |
| ADHD | [e.g. "5-minute version: Phases 1–2 + 5 core interactions only"] |
| Dyslexia | [e.g. "OpenDyslexic font option active. All text audio-first."] |
| Fine Motor | [e.g. "Tap alternatives available for all drag interactions"] |

---

## Asset Requirements

| Asset | Type | Description | Status |
|---|---|---|---|
| Background | Illustration | [Describe the scene/setting] | Needed |
| [Item name] | Sprite | [Describe what it is] | Needed |
| Kivi | SVG | [Which KV asset and in which phases] | Pending illustrator |

---

## Pre-Publish Checklist

Before submitting for Review, confirm every item:

**Metadata**
- [ ] `id` assigned by content lead
- [ ] `title` is fun and world-themed — not a database label
- [ ] `learningObjective` is exactly ONE string starting with a verb
- [ ] `rewardPoints`, `gemReward`, `coinReward` all set to correct tier values
- [ ] `kiviAsset` specified for every reward/celebration moment
- [ ] `duration` is ≤ 10 minutes
- [ ] `audioRequired: true` confirmed

**Content**
- [ ] Hook has a vivid scene description and Kivi speech ≤ 12 words
- [ ] Warm-Up has 2 interactions, no score recording
- [ ] Core Learning has exactly 10 interactions
- [ ] Hint appears on 2nd wrong attempt (not 1st, not withheld)
- [ ] Wrap-Up shows XP + Coins + Kivi celebration
- [ ] No countdown timers anywhere
- [ ] No score shown during activity — only at wrap-up
- [ ] No FOMO/scarcity/pressure language

**Accessibility**
- [ ] Tested at Toddler profile (if applicable)
- [ ] Tested at ADHD profile
- [ ] Tested at Dyslexia profile
- [ ] All tap targets ≥ 44×44px (64px for Toddler tier)
- [ ] All text has audio read-aloud

**Reviewer sign-off**
- Reviewed by: ________________
- Date: ________________
- Status: ☐ Approved  ☐ Return to Draft — Notes: ________________
