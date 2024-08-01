# Mad Alex's Whimsical Process

## welcome!

are you an avid reader in search of more stories by Mad Alex? if so, go on right ahead and navigate to the `downloadable-contents` folder and peruse at your leisure. All pdfs are available for free download. if you enjoy what you read, consider purchasing the story on Apple Books. all short stories are available for .99 USD; they're inexpensive and you'll be supporting my writing. you are also welcome to tap the sponsor link up at the top and contribute directly to this repository, which will also support my work. the README in the same folder as the stories contains the links to each.

thank you for dropping in, and stay mad as cat, my delectable little voracious bibliophages!

the rest is just boring notation for anyone who's interested in how i manage my writing projects.
## the writing process

all writing projects, all the time. each project is housed in its respective directory. avoid linkages between files in separate directories
### workflow

1. close obsidian after every session to trigger daily note on next session startup
2. each session is recorded on a separate branch. `git teleport -b [new branch name]` prior to opening obsidian
3. each project operates in its own repository; projects are added as submodules
	1. work within each respective project folder and commit and push changes accordingly
4. daily note = `CHANGELOG`; all updates, additions, and modifications to projects should be recorded in the daily note upon session completion
5. OMG, Write!!!
6. `git add .` and `git commit -m` and `git push` upon completion
7. merge branch into `main` on github.
### working copy
do not work directly in `main`. working copy is branched from `main`, then pushed to github for review and merge

