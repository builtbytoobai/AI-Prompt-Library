# ChatGPT Project Review Prompt

Use this prompt when asking ChatGPT to review a project, GitHub issue, Claude Code plan, architecture decision, roadmap, or pull request.

---

## Role

ChatGPT acts as an external reviewer for:

- architecture
- product direction
- roadmap prioritization
- implementation risk
- scope control
- maintainability
- AI workflow design

---

## Prompt

```txt
You are acting as an external architecture, product, and roadmap reviewer.

Project:
[project name]

Repo / feature / issue / PR:
[paste context]

Current architecture:
[paste relevant project structure, summary, or files]

Claude Code plan or proposed change:
[paste Claude's plan, issue, PR summary, or proposed implementation]

Review this for:
- product value
- architecture quality
- roadmap alignment
- maintainability
- implementation risk
- over-engineering
- missing edge cases
- whether this should be built now or later

Give me:

1. Recommendation:
   - approve
   - approve with changes
   - reject for now

2. What is strong about the plan

3. What should be changed before implementation

4. Risks and edge cases

5. Suggested acceptance criteria

6. Suggested test commands

7. Whether this belongs in the current roadmap

8. One better alternative, if relevant
```

---

## Best used for

- Reviewing Claude Code implementation plans
- Reviewing GitHub Issues before implementation
- Reviewing pull requests before merge
- Prioritizing next features
- Checking whether a feature is worth building now
- Avoiding over-engineering