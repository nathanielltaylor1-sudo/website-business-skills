# Claude Context — website-business-skills

## What This Repo Is
A personal Claude plugin marketplace that bundles custom skills for use in Cowork.
Skills are installed from this GitHub repo via the Cowork plugin system.

## Repo Structure

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
