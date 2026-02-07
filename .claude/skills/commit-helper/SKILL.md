---
name: commit-helper
description: Use when the user asks to commit changes. Ensures clean, well-scoped commits.
disable-model-invocation: true
---

When creating a commit, follow these rules:

1. **Review staged changes** -- Read the diff. Make sure only relevant files are staged. Never stage `.env`, credentials, or large binaries.
2. **One concern per commit** -- If the changes cover multiple unrelated things, suggest splitting into separate commits.
3. **Write a clear message** -- Summarize the "why" not the "what". Use imperative mood (e.g., "Add", "Fix", "Remove"). Keep the subject line under 72 characters.
4. **Never amend unless asked** -- Always create new commits. Amending can destroy previous work.
5. **Never force push** -- Unless the user explicitly requests it.
6. **Verify success** -- Run `git status` after committing to confirm it worked.
