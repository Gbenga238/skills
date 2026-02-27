# writing-spec skill

Use this skill to create or refine feature specs with a strict flow:
1. Requirements
2. Technical design
3. Implementation tasks

## Install / discover skills

Use `npx skills` for install and verification:

```bash
# Install a specific skill
npx skills add vercel-labs/agent-skills@<skill-name>

# Install from a GitHub repo
npx skills add <owner/repo>

# List installed skills (local)
npx skills list

# List installed skills (global)
npx skills ls -g

# Install globally
npx skills add <owner/repo> -g

# Install to a specific agent
npx skills add <owner/repo> -a <agent-name>
```

Default install paths are usually `./.claude/skills` or `./.agent/skills`.

Then proceed with the workflow in [`SKILL.md`](./SKILL.md).
