# PR External Review Template

Use this when asking an external AI reviewer to evaluate a pull request.

---

## Template

```txt
Review this pull request as an external reviewer.

Repository:
[repo name]

PR title:
[title]

PR summary:
[paste summary]

Files changed:
[paste files changed]

Diff or relevant code:
[paste important diff/code]

Test results:
[paste local tests and GitHub checks]

Review for:
- correctness
- maintainability
- whether the change is too large
- missing tests
- missing docs
- security/secrets issues
- whether it follows the project direction

Give me:
- approve / approve with changes / reject
- required changes before merge
- optional improvements
- questions I should ask Claude before merging
```