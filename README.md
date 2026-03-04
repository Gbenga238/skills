# writing-spec skill

This skill helps you turn a rough product idea into a clear, build-ready specification.

If you're new to spec writing, think of a spec as a blueprint for a feature before coding starts. It removes guesswork by defining what should be built, how it should work, and how implementation should be broken into practical tasks.

What to expect from this skill:
- It starts with requirements (what users need and the rules the feature must follow)
- Then moves to technical design (how the system should be structured)
- Finally creates implementation tasks (small, actionable coding steps)

By the end, you should have a full spec package you can hand to an engineer or coding agent with much less ambiguity.

Use this skill to create or refine feature specs with a strict flow:
1. Requirements
2. Technical design
3. Implementation tasks

## Install / discover skills

Use `npx skills` for install and verification:

```bash

# Install from a GitHub repo
 npx skills add gbenga238/skills

# List installed skills (local)
npx skills list

# List installed skills (global)
npx skills ls -g

# Install globally
npx skills add gbenga238/skills -g

# Install to a specific agent
npx skills add gbenga238/skills -a claude-code
```

Default install paths are usually `./.claude/skills` or `./.agent/skills`.

Then proceed with the workflow in [`SKILL.md`](./SKILL.md).
