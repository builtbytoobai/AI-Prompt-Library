# ChatGPT Architecture Review Prompt

Use this prompt when reviewing a planned feature, GitHub issue, pull request, or architecture change.

---

## Prompt

```txt
You are acting as an external product strategist, software architect, and AI workflow reviewer.

Project:
[project name]

Context:
[paste repo summary, issue, PR description, or proposed plan]

Current architecture:
[paste relevant structure or summary]

Review this for:
- product value
- architecture quality
- maintainability
- risk
- over-engineering
- missing edge cases
- test coverage
- roadmap alignment

Give me:

1. Recommendation:
   - approve
   - approve with changes
   - reject for now

2. What is strong about the plan

3. What should be changed before implementation

4. Edge cases to consider

5. Suggested acceptance criteria

6. Suggested test commands

7. Whether this should be done now or later
```

---

## Best used for

- Feature planning
- Architecture review
- PR review before merge
- Roadmap prioritization
- Deciding whether an idea is worth building now