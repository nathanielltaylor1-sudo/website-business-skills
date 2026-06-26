# Claude Context — website-business-skills

## What This Repo Is
A personal Claude plugin marketplace that bundles custom skills for use in Cowork.
Skills are installed from this GitHub repo via the Cowork plugin system.

## Repo Structure

That's because your local terminal is a separate environment from this cloud session — the `CLAUDE.md` file and the commit only exist here, not on your machine.

The easiest fix is to create the file directly on GitHub:

1. Go to your repo on GitHub: `github.com/nathanielltaylor1-sudo/website-business-skills`
2. Click **Add file** → **Create new file**
3. Name it `CLAUDE.md`
4. Paste this content:

```markdown
# Claude Context — website-business-skills

## What This Repo Is
A personal Claude plugin marketplace that bundles custom skills for use in Cowork.
Skills are installed from this GitHub repo via the Cowork plugin system.

## Repo Structure
```
AL-Design/          <- design-focused skills (clone, gsap, shadcn, marketing-ui, functional-ui)
plugins/
  business-tools/
    skills/         <- custom business skill definitions (SKILL.md per skill)
README.md           <- setup instructions for Cowork plugin install
```

## My Skills (Available via "/")
- **clone** — Clone an existing UI from screenshots or a public page's real code
- **functional-ui** — Build functional app UIs
- **marketing-ui** — Build landing/marketing pages
- **gsap** — Animation with GSAP/ScrollTrigger
- **shadcn** — Component work with shadcn/ui

## How to Add a New Skill
1. Create a folder under `plugins/business-tools/skills/<skill-name>/`
2. Add a `SKILL.md` with `name` and `description` frontmatter
3. Commit and push
4. In Cowork: click "Update" on the marketplace to resync

## Preferences
- Keep responses short and direct
- No unnecessary comments in code
- No emojis unless asked
- Prefer editing existing files over creating new ones
- Don't add features or abstractions beyond what's asked

## Google Drive
Claude information, skills index, and preferences are also stored in Google Drive
under the "Claude" folder for cross-device access.
```

5. Click **Commit changes** directly to `main`

That will clear the hook and make `CLAUDE.md` available to every future session automatically.
## My Skills (Available via "/")
- **clone** — Clone an existing UI from screenshots or a public page's real code
- **functional-ui** — Build functional app UIs
- **marketing-ui** — Build landing/marketing pages
- **gsap** — Animation with GSAP/ScrollTrigger
- **shadcn** — Component work with shadcn/ui

## How to Add a New Skill
1. Create a folder under `plugins/business-tools/skills/<skill-name>/`
2. Add a `SKILL.md` with `name` and `description` frontmatter
3. Commit and push
4. In Cowork: click "Update" on the marketplace to resync

## Preferences
- Keep responses short and direct
- No unnecessary comments in code
- No emojis unless asked
- Prefer editing existing files over creating new ones
- Don't add features or abstractions beyond what's asked

## Google Drive
Claude information, skills index, and preferences are also stored in Google Drive
under the "Claude" folder for cross-device access.
