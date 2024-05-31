# the joshuaalexander obsidian vault

## summary

all writing projects, all the time. each project is housed in its respective directory. avoid linkages between files in separate directories

## workflow

1. close obsidian after every session to trigger daily note on next session startup
2. each session is recorded on a separate branch. `git teleport -b [new branch name]` prior to opening obsidian
3. daily note = `CHANGELOG`; all updates, additions, and modifications to projects should be recorded in the daily note upon session completion
4. OMG, Write!!!
5. `git add .` and `git commit -m` and `git push` upon completion
6. merge branch into `main`

## working copy
do not work directly in `main`. working copy is branched from `main`, then pushed to github for review and merge

