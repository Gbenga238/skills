# writing-spec skill

Build clear, execution-ready specs before writing implementation code.

If you're new to specs: this is the planning layer between "idea" and "code."
It helps you define what should be built, what success looks like, and the safest path to implement it.

Our philosophy:
- -> clear over clever
- -> iterative refinement over one-shot plans
- -> practical outputs over documentation theater
- -> works in real, existing codebases
- -> useful for solo builders and teams

What this skill does:
1. Creates requirements (`requirements.md`) with clear user stories + acceptance criteria
2. Builds technical design (`design.md`) covering architecture, models, interfaces, and testing
3. Generates implementation tasks (`tasks.md`) as actionable coding steps

What to expect:
- You start with a rough feature idea
- The workflow converts it into structured planning artifacts
- You review and approve each artifact before the next phase
- You finish with a concrete implementation checklist for engineers or coding agents

> Tip
> This skill follows a strict 3-stage flow: requirements -> design -> tasks.
> It is planning-first and intentionally does not implement feature code.

## See it in action

You: "Add a document tagging feature."

AI:
- Creates `.kiro/specs/document-tagging/requirements.md`
- Creates `.kiro/specs/document-tagging/design.md`
- Creates `.kiro/specs/document-tagging/tasks.md`
- Requests approval at each stage before continuing

Ready to execute after approval: open `tasks.md` and implement items in order.

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
