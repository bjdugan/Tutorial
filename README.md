# Git Tutorial

## Formatting MD


## Git Workflow
* `git clone https://github.com/USER/REPO.git` copies the (remote?) directory to cur dir
* `git status` shows what's been modified and if dir/repo is ahead or behind master
* `git add origin master` queues origin to be merged with master (or remote repo, https...)
* `git fetch https://...` provides the most recent snapshot of data in remote repo to local repo; does not integrate (must be `merged`)
* `git commit -m "Some comment"` approves of queued (added) items to be merged
* `git push origin master` merges items in origin (working dir) to master (https)
* `git pull https://...` acts like push, but copies from master repo (github) to local, i.e., fetches and merges. This can cause merge conflicts.

Working on a project: CLONE (new) > FETCH (?) > EDIT > ADD > COMMIT > PUSH

![Git File Lifecycle](./git-lifecycle.png)
From [git-scm.com](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository)




