git init - initialize an existing directory as a Git repository

git status - show modified files in working directory, staged for your next commit

git add [file] - add a file as it looks now to your next commit

git reset [file] - unstage a file while retaining the changes in working directory

git diff --staged - diff of what is staged but not yet commited

git commit -m “[name]” - commit your staged content as a new commit

git branch - list your branches. a * will appear next to the currently active branch

git checkout - switch to another branch and check it out into your working directory

git merge [branch] - merge the specified branch’s history into the current one

git log - show all commits in the current branch’s history

git rm [file] - delete the file from project and stage the removal for commit

git mv [existing-path] [new-path] - change an existing file path and stage the move

git log --stat -M - show all commit logs with indication of any paths that moved

git reset --hard [commit] - clear staging area, rewrite working tree from specified commit