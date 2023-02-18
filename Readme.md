Git&Github commands

In this repository I'll put all my notes about git and github.

#File Status Lifecycle
    untracked, unmodified, modified, staged

git status - shows repository's info
git add - moves files to stage
git commit -m "message" - record changes to the repository
git log --author="" - commits by author
git shortlog --graph - graphic of commits tree

git show <hash> - a specific commit

git diff - changes made on the repository since last commit
git diff --name-only - names of the files changed on the repository

git checkout <file> - if the selected file is  unstaged, this command undo changes made since last commit
git reset Head <file> - removes file from staged status
git reset --soft <hash> - undo commit right after selected commit(hash) and return files to stage
git reset --mixed <hash> - undo commit right after selected commit and return files to modified status (before staged)
git reset --mixed <hash> - undo commit since last commit(hash)

