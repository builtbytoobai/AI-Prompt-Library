# Pull Request External Review Template

Use this when asking ChatGPT or Gemini to review a pull request before merge.

---

## Template

```txt
Review this pull request as an external reviewer.

Repository:
[repo name]

PR title:
[PR title]

PR summary:
[paste PR summary]

Files changed:
[paste list of changed files]

Important diff or code:
[paste relevant diff/code]

Test results:
[paste local test results and GitHub checks]

Project direction:
[paste relevant roadmap or goal]

Review for:
- correctness
- maintainability
- scope control
- whether unrelated files changed
- missing tests
- missing documentation
- security or secrets issues
- whether this fits the project direction
- whether this should be merged now

Give me:

1. Recommendation:
   - approve
   - approve with changes
   - reject for now

2. Required changes before merge

3. Optional improvements

4. Risks or edge cases

5. Questions I should ask Claude Code before merging

6. Suggested follow-up issue, if relevant
```

---

## Best used for

- PR review before merge
- Checking Claude Code output
- Reviewing larger changes
- Catching missed docs/tests
- Keeping the repo clean and focused