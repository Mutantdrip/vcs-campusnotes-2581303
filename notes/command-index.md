# Git command index

## Remotes and tracking

| Task | Command |
| --- | --- |
| Inspect fetch and push URLs | `git remote -v` |
| Publish main and track origin | `git push -u origin main` |
| Update from the tracked branch | `git pull --ff-only` |

## Tags and hooks

| Task | Command |
| --- | --- |
| List tags with annotations or commit subjects | `git tag -n` |
| Configure shared hooks | `git config core.hooksPath .githooks` |
