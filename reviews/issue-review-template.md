# GitHub Issue Review Template

Use this before asking Claude Code to implement a GitHub Issue.

---

## Template

```txt
Review this GitHub Issue before I ask Claude Code to implement it.

Repository:
[repo name]

Issue title:
[issue title]

Issue description:
[paste issue description]

Current project state:
[paste short repo summary or relevant architecture]

Review for:
- whether the issue is clear
- whether the scope is too large
- missing acceptance criteria
- missing edge cases
- risk of over-engineering
- files likely affected
- whether this should be done now or later

Give me:

1. Recommendation:
   - ready for Claude Code
   - needs clarification
   - too large / split it up
   - not worth doing now

2. What should be clarified

3. Suggested acceptance criteria

4. Suggested implementation boundaries

5. Suggested test commands

6. Suggested branch name

7. Suggested PR title
```

---

## Best used for

- Cleaning up issues before implementation
- Turning vague ideas into clear Claude Code tasks
- Reducing scope before coding starts
- Avoiding messy PRs