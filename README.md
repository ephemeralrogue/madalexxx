# the nonsensetwice obsidian vault

## summary

git is the key to accessing all the content. everything's distributed across different branches for focus. `content/*` branches contain the core project files of whatever is in focus. `update-*` branches are the working copy; upon completion each day, `update-*` branch is merged into `content/*` branch. `content/*` branches are protected; pushing work from `update-*` branches help keep the commit history clean.

there are currently two special branches: `main` and `CHANGELOG`.
- `main` holds all the vital docs that are relevant across the entire workspace: `.gitignore`, `README`, etc. whenever any of these documents require editing, or new documents are added, an `update-main` branch is created where all the edits are made and the merged with `main` and all `update-*` branches. `update-*` branches will subsequently be merged with their `content/*` counterparts.
- daily notes are filled out in the `CHANGELOG` branch. 

## workflow

1. `git status`; make sure `CHANGELOG` is checked out before opening vault
2. open vault to populate daily note; commit changes
3. checkout working copy; copy branch for edits
4. do work; commit changes; push to home; merge to working copy
5. checkout `CHANGELOG`; fill out daily note; commit changes; push to home

## working copy
`update-*` branches are the working copy. if an `update-*` branch does not exist for the `content/*` branch, create one. merge updates at the [git repo](https://github.com/ephemeralrogue/nonsensetwice.obsidian) for each *content/update* pair at the end of each work session.

### children of the damned
`git teleport update-children`

### dungeons and dragons
`git teleport update-dnd`

### writing prompts
`git teleport update-prompts`

