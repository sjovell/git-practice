# Practice repository to start learning Git

## Commands used

- git init: Create a new git repository
- git status: Compare working directory, staging area, and current branch
- git add: Add changes from working directory to staging area
- git commit: Commit changes from staging area to current branch
- git config: Set or get configuration
- git log: Show a history (aka "log") of project commits
- git checkout: Check out branch (update HEAD and apply changes to working directory)
- git merge: Merge changes from different branches

## Commit messages

Default editor is vim (this can be chanced)
  - `i` to enter *insert* mode
  - Type commit messages
  - `Esc` -> `:wq` -> `Enter` to write message and quit
Or use `git commit -m "<message>"`

- First line should be clear, accurate, and concise
- Use proper spelling, grammar, and punctuation
- Don't end with a `.`

For more advice, see: https://chris.beams.io/posts/git-commit/

## Merging

Merging means to bring the changes from one branch into another.

- A fast-forward merge happens when the target branch was branched from the current one, and there are no new changes to current branch since then.
- An Automatic merge happens when two histories have diverged, but git is able to reconcile them into one set of changes. This creates a new commit on the current branch.
