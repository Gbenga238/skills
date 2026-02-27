# writing-spec skill

Use this skill to create or refine feature specs with a strict flow:
1. Requirements
2. Technical design
3. Implementation tasks

## Install / discover skills

Use `npx skills` for install and verification:

```bash

# Install from a GitHub repo
npx skills add gbenga238/writing-spec

# List installed skills (local)
npx skills list

# List installed skills (global)
npx skills ls -g

# Install globally
npx skills add gbenga238/writing-spec -g

# Install to a specific agent
npx skills add gbenga238/writing-spec -a claude-code
```

Default install paths are usually `./.claude/skills` or `./.agent/skills`.

Then proceed with the workflow in [`SKILL.md`](./SKILL.md).
