---
# QUIZ METADATA — fill every field before submitting for Review
id:               ""                  # QZ-NNN  (assigned by content lead)
title:            ""                  # e.g. "Number Knowledge: 1 to 10"
type:             quiz
subject:          ""
world:            ""
ageGroup:         ""
grade:            ""
difficulty:       ""
questionCount:    10                  # Always 10
duration:         10                  # Always 10 minutes (internal timer only — never shown to child)
skills:           []
learningObjective: ""                 # EXACTLY ONE string
rewardPoints:     0
gemReward:        1                   # Quizzes always award at least 1 Gem (quizzes are skill-check moments)
coinReward:       0                   # Set per tier; coins are NOT reduced for low scores
kiviAsset:        KV-005              # Intro: KV-005 (think). Results: KV-004 (celebrate) or KV-003 (happy)
audioRequired:    true
accessibilityFlags: []
offlineAvailable: false
status:           draft
createdBy:        ""
reviewedBy:       ""
lastUpdated:      ""
---

# [TITLE]

## Challenge Intro (30 seconds, KV-005)

> **Kivi says**: "[Intro line — inviting, no pressure. Max 12 words. e.g. 'Kivi has 10 questions — let's see how much you know!']"

**Screen description**: [What does the child see? What world/theme visuals set the mood?]

> ⚠️ **Rules enforced by this quiz**:
> - No timer shown to child at any point
> - Score not shown during questions — only at results screen
> - Stars (1–3), never percentages, shown to child
> - Coins awarded equally regardless of score band
> - Retry available immediately, no cooldown

---

## Questions

> Use a minimum of **2 different question types** across 10 questions.
> Available types: Multiple Choice (4 options) | True/False | Image Match | Audio Match | Sequence | Fill in the Blank | Short Answer (AI-graded, Grade 3–5 only)

---

### Question 1

**Type**: [Multiple Choice / True-False / Image Match / Audio Match / Sequence / Fill-in-Blank / Short Answer]
**Prompt**: [Exact question text — also the audio read-aloud script]
**Visual**: [Describe what's on screen alongside the question]

**Options** *(for Multiple Choice — mark correct with ✓)*:
- [ ] A.
- [ ] B.
- [✓] C.
- [ ] D.

**Correct answer**: 
**Kivi micro-reaction on correct** (5 sec, between questions): [brief description e.g. "small wiggle + ⭐ flash"]
**Kivi micro-reaction on wrong** (5 sec, between questions): [brief description e.g. "gentle head-tilt, no negative sound"]

> ℹ️ Micro-reactions are between questions only. No immediate feedback mid-question in quiz mode.

---

### Question 2

**Type**: 
**Prompt**: 
**Visual**: 
**Options**:
-
-
-
-
**Correct answer**: 
**Kivi micro-reaction on correct**: 
**Kivi micro-reaction on wrong**: 

---

### Question 3

**Type**: 
**Prompt**: 
**Visual**: 
**Options / answer**:
**Correct answer**: 
**Kivi micro-reaction on correct**: 
**Kivi micro-reaction on wrong**: 

---

### Question 4
[repeat structure]

### Question 5
[repeat structure]

### Question 6
[repeat structure]

### Question 7
[repeat structure]

### Question 8
[repeat structure]

### Question 9
[repeat structure]

### Question 10
[repeat structure]

---

## Results Screen (90 seconds, KV-004)

> ⚠️ **Rule**: Show stars (⭐⭐⭐ / ⭐⭐ / ⭐) — NEVER show a percentage to the child.
> ⚠️ **Rule**: Big celebration animation regardless of score band. Every child gets a moment.

### Score Bands

| Stars | Score Range | Kivi Message (max 12 words) | Coins |
|---|---|---|---|
| ⭐⭐⭐ | 100% (10/10) | "[Your celebration message for perfect score]" | [coinReward] + 5 bonus |
| ⭐⭐ | 60–99% (6–9/10) | "[Your encouragement message for good score]" | [coinReward] |
| ⭐ | 0–59% (0–5/10) | "[Your 'great start' message — zero shame]" | [coinReward] — same, never reduced |

**Gems awarded on any completion**: [gemReward] (always awarded for attempting, regardless of score)
**XP awarded**: [rewardPoints]

**CTA buttons shown**:
- "Try Again" (always visible, no cooldown)
- "Review My Answers" (leads to Review Mode)
- "Next Activity" (leads to [linked activity slug])

---

## Review Mode (optional, 5 minutes, KV-005)

When child taps "Review My Answers":
- Shows each wrong answer with a gentle Kivi explanation
- Earns bonus Coins for completing Review Mode: +3 Coins

**Review explanations** (write one per question that could be wrong):

| Q# | Brief explanation Kivi gives (max 20 words, child-facing language) |
|---|---|
| Q1 | |
| Q2 | |
| Q3 | |
| Q4 | |
| Q5 | |
| Q6 | |
| Q7 | |
| Q8 | |
| Q9 | |
| Q10 | |

---

## Pre-Publish Checklist

**Metadata**
- [ ] Exactly 10 questions
- [ ] `gemReward` is ≥ 1 (quizzes always award at least 1 gem)
- [ ] `coinReward` is set for the difficulty tier
- [ ] Exactly ONE learning objective

**Content**
- [ ] Minimum 2 different question types used
- [ ] No timer shown to child at any point
- [ ] Score not shown during questions
- [ ] Results use ⭐ stars only — no percentage
- [ ] All 3 score-band Kivi messages written — none shame, all encouraging
- [ ] Coins are the same for all score bands (confirmed not reduced for low scores)
- [ ] Retry available immediately
- [ ] Review Mode explanations written for all 10 questions

**Reviewer sign-off**
- Reviewed by: ________________
- Date: ________________
- Status: ☐ Approved  ☐ Return to Draft — Notes: ________________
