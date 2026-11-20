# dev-repo

Recipe repository for `dev recipe`.

Layout:

- `repository.yml` — index of recipes.
- `recipes/<file>.yml` — recipe files in the custom-command format (`commands:` map).

Point `dev` to this repository in `~/dev-command/main.conf`:

```ini
recipe-repo=/work/dev-repo
```

Then run:

```bash
dev recipe
dev recipe deploy
dev recipe --force deploy
```
