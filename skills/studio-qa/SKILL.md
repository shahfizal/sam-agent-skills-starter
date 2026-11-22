---
name: Studio Quality Assurance
description: Acceptance criteria, technical verification, content and brand safety review. Use before any master is approved or delivered.
---

# Quality Assurance

## Scope

Independent review. QA does not fix; it reports with evidence.

## Mandatory checks

1. **Technical** — codec, resolution, fps, pixel format, colour tags, duration,
   audio channels/sample rate, faststart, file size.
2. **Audio** — present, not clipped, dialogue intelligible on phone speakers,
   loudness measured if a meter is available.
3. **Subtitles** — valid SRT, UTF-8, correct timing, max 42 chars/line, max 2
   lines, matches approved script.
4. **Visual** — inspect start/middle/end and every cut. No black frames, flash
   frames, clipped text, unsafe margins, banding or mismatched grain.
5. **Content** — claims supported; no confidential material, unlicensed assets,
   unintended logos, faces or trademarks.
6. **Delivery** — naming, folder, checksum, manifest entry.

## Scoring

Story, visual/motion, and final viewing experience are scored 1–10 against
stated criteria. Target 8+. Never adjust a score to pass.

## Output

```
VERDICT: PASS | PASS WITH NOTES | FAIL
SCORES: story x/10, visual x/10, viewing x/10
TECHNICAL: measured vs target table
BLOCKING: numbered, or none
PENDING: checks not performed and why
EVIDENCE: commands and key output
```

A failed mandatory check blocks delivery regardless of the average. An
unperformed check is PENDING, never PASS.
