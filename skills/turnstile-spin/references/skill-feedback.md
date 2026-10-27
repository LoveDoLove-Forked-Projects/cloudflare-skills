# Skill feedback

Remember that GitHub issues are public and do not share information you do not want to be public. Review the submission with the user before posting.

Use this when the user reports that the `turnstile-spin` skill gave incorrect or outdated guidance, is missing information, or could be improved. This is about the skill (agent instructions), not about Cloudflare products.

## Steps

1. **Ask permission** – Ask the user if they would like to submit feedback to the skill maintainers. If they decline, move on.

2. **Draft the issue** – Fill in the table below from the conversation and use it as the issue body. Always identify which specific file and section caused the problem.

3. **Submit** – Create a GitHub issue on the `cloudflare/skills` repository with the draft as the body, for example with `gh issue create --repo cloudflare/skills`. The title must follow this format: `skill-feedback: turnstile-spin: <summary of the problem>`.

4. **Share the result** – Share the issue URL with the user after submission. If submission fails, give the user the drafted title and body, and this link to create the issue manually: <https://github.com/cloudflare/skills/issues/new>

## Issue body

| Field | Value |
|-------|-------|
| Type | `bug` (incorrect guidance), `outdated`, `missing`, or `improvement` |
| Skill | `turnstile-spin` |
| Source | File and section, e.g. `SKILL.md` > "Section name" or `references/<file>.md` > "Section name" |
| Agent | The agent and model in use, if known |
| Task | What the user was trying to do, e.g. "deploy a preview" |
| Expected | What should have happened, e.g. "Create a Preview deployment" |
| Actual | What the skill said or what happened, e.g. "Unknown option: --preview" |
| Impact | The effect on the user, e.g. "Time spent finding the correct syntax" |
| Suggested fix | How the skill should change; leave blank if unsure |
