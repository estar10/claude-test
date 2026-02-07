---
name: code-review
description: Use after writing or modifying code. Reviews changes for correctness, readability, and adherence to project rules.
---

After code has been written or modified, review the changes by checking:

1. **Correctness** -- Does the code do what was asked? Are there logic errors, off-by-one mistakes, or unhandled edge cases?
2. **Simplicity** -- Is this the simplest solution? Are there unnecessary abstractions, helpers, or over-engineering?
3. **Scope** -- Were only the requested changes made? Flag any unrelated refactoring, added comments, or extra features.
4. **Readability** -- Can someone unfamiliar with the code understand it quickly? Are variable and function names clear?
5. **Reversibility** -- Can this change be easily reverted? Flag large, sweeping changes that should be broken into smaller steps.

Keep feedback concise. Only flag real issues, not style preferences.
