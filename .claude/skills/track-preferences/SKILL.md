---
name: track-preferences
description: Use when the user expresses a preference about how work should be done, such as coding style, communication style, tooling choices, or workflow habits.
---

When the user states a preference (explicitly or through repeated corrections):

1. **Check `.claude/preferences.md`** -- Is this preference already recorded?
2. **If not, add it** -- Append a short entry:

```
### [Category]: [Preference]
- **Preference:** [What the user wants]
- **Context:** [When this applies]
```

Categories include: coding style, communication, workflow, tools, git, testing, etc.

Always read `.claude/preferences.md` before starting work to respect established preferences. Never argue with a stated preference -- just record it and follow it.
