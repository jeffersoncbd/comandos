# Fábio Akita - git

- git commit -m "message" --amend       - fix the message of last commit
- git reset --soft HEAD~N               - undo N commits keeping changes
- git rebase -i HEAD~N                  - rebase N commits
- git reset -- FileName                 - remove file from stage
- git add -i                            - interactive control of the stage
- git add -p                            - add chunks of files (partial)
- git reset --hard HEAD~N               - delete N commits
- git checkout -b BranchName sha1       - recovery deleted commit and adds it to a new branch
- git checkout BranchName               - go to the indicated branch
- git rebase BranchName                 - unify branch indicated in actually branch
- git branch -d BranchName              - delete branch
