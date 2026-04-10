---
name: motion-brief
description: >
  Use when the Motion Designer needs to translate the Visual Designer's static asset
  specs and motion cues into a concrete animation brief before producing deliverables.
  Triggered after Visual Designer has @mentioned Motion Designer with asset specs.
---

# Motion brief

## Purpose
Before animating anything, define the motion language. This prevents inconsistency across animated assets and ensures motion serves the brand, not just fills time.

## Output structure

```
## Motion brief — [Project name]

### Motion language
**Energy**: [slow / medium / fast — and what that means for this brand]
**Easing**: [ease-in-out / spring / linear / custom — with visual description]
**Personality**: [how things move — snap, drift, bounce, breathe, unfold]
**Duration guideline**: [micro: Xms / transitions: Xms / reveals: Xms]

### Animation principles for this campaign
[3-5 specific rules that define how this brand moves. Example:]
- "Text reveals happen word by word, not letter by letter"
- "Elements enter from the bottom, not the sides"
- "Nothing bounces — the brand is confident, not playful"

### Asset animation specs

For each asset from Visual Designer:

**[Asset name]**
- Format: [MP4 / GIF / Lottie / WebM]
- Dimensions: [from Visual Designer spec]
- Duration: [Xs]
- Loop: [yes/no — if yes, seamless or with pause]
- File weight target: [max MB/KB]
- Key animation moments:
  1. [0:00-0:02] — [what happens]
  2. [0:02-0:05] — [what happens]
  3. [0:05-0:08] — [what happens, CTA or end card]
- Sound: [yes/no — if yes, describe tone]
- Platform destinations: [where this will be used]

### Storyboard (text description)

[For each key animation, describe frame by frame in plain language:]

Frame 1 (0:00): [description of what's on screen]
Frame 2 (0:02): [transition — what moves, how, what appears]
...
Final frame: [end state — CTA visible, brand mark present]
```

## Rules
- Duration must match platform specs from Content Strategist calendar (e.g., Instagram story = 15s max).
- File weight targets are non-negotiable — oversized files kill performance.
- Every animation must start and end on a stable frame (no mid-motion cuts at loop points).
- If Visual Designer's motion cues are ambiguous, @mention Visual Designer before producing — do not guess.
