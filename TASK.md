# TASK.md

## What This Project Is

This is a new project workspace (`claude-test`). It serves as a development sandbox for building and iterating on ideas with the help of Claude Code. The repository is currently in its early stages with no established codebase, meaning all structure and conventions will be defined as work progresses.

## Rules for Modifying Code

Follow these rules whenever making changes in this repository:

1. **Read before writing.** Never modify a file you haven't read first. Understand existing code before changing it.
2. **Stay on task.** Only make changes that are directly requested or clearly necessary. Do not refactor, add features, or "improve" code beyond what was asked.
3. **Don't over-engineer.** Avoid adding abstractions, utilities, or helpers for one-time operations. Avoid designing for hypothetical future requirements.
4. **No unnecessary files.** Do not create new files unless absolutely required. Prefer editing existing files.
5. **No security vulnerabilities.** Do not introduce command injection, XSS, SQL injection, or other common vulnerabilities. Fix any that are noticed immediately.
6. **Keep it simple.** Three similar lines of code are better than a premature abstraction. The right amount of complexity is the minimum needed for the current task.
7. **Don't add noise.** Do not add docstrings, comments, or type annotations to code you didn't change. Only add comments where logic isn't self-evident.
8. **Clean deletions.** If something is unused, delete it completely. No backwards-compatibility hacks, no `// removed` comments, no renaming to `_unused`.

## Small, Reversible Changes

This is the most important principle. Every change should be:

- **Small** -- Do one thing at a time. A single, focused change is easier to understand, review, and debug than a large batch of edits.
- **Reversible** -- Prefer changes that can be easily undone. If something goes wrong, it should be straightforward to revert to the previous working state.
- **Incremental** -- Build up functionality step by step. Verify each step works before moving to the next. Don't make sweeping changes all at once.

When in doubt, make the smaller change. A series of small, correct steps will always get you further than one big risky leap.
