---
name: learn-from-corrections
description: Use when the user corrects a mistake, rejects an approach, or points out something wrong. Captures the lesson so it is not repeated.
---

When the user corrects you or points out an error:

1. **Acknowledge the mistake** concisely. Do not over-apologize.
2. **Identify the root cause** -- Why did the mistake happen? Wrong assumption? Missed context? Over-engineering?
3. **Fix the issue** immediately.
4. **Log the lesson** -- Append a short entry to `.claude/lessons.md` in this format:

```
### YYYY-MM-DD: [Short title]
- **What went wrong:** [One sentence]
- **Why:** [Root cause]
- **Rule:** [What to do differently next time]
```

Always read `.claude/lessons.md` at the start of a session to avoid repeating past mistakes.
