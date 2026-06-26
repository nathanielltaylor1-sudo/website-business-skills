# Website Business Skills

A personal Claude plugin marketplace. It bundles custom skills so they can be
installed in Cowork directly from this GitHub repo.

## Structure

```
.claude-plugin/
  marketplace.json          <- lists the plugin(s) in this repo
plugins/
  business-tools/
    .claude-plugin/
      plugin.json           <- describes the plugin
    skills/
      example-skill/
        SKILL.md            <- one folder per skill
```

## Add a new skill

Create a new folder under `plugins/business-tools/skills/`, e.g.
`skills/invoice-helper/`, containing a `SKILL.md` with `name` and `description`
frontmatter. Commit it.

## Use it in Cowork

1. Cowork -> Customize -> Plugins -> Personal plugins -> "+" -> Add marketplace -> Add from a repository.
2. Paste this repo's URL and let it sync.
3. Browse plugins -> Install "business-tools".
4. Type "/" to see the skills. After pushing changes, click "Update" on the marketplace to resync.
