# Git Pointers
Git commands for when I got lost during work..

| I want to..                | Git Commands                                       | Notes                                                           |
|----------------------------|----------------------------------------------------|-----------------------------------------------------------------|
| Get a repo                 | `$git clone url_from_gitHub`                         |                                                                 |
| Get a remote branch        | `$git clone -b branch_name url_from_gitHub`          | Or try `$git pull` and `$git checkout remote_branch_name`       |
| Create a new branch        | `$git checkout -b new_branch_name`                   |                                                                 |
| Go to a branch             | `$git checkout branch_name`                          | The name must exactly match                                     |
| Make a commit              | `$git add <files>`                                   | When committing to a branch for the first time,                 |
|                            | `$git commit -m "some message"`                      | follow the suggestion for push command                          |
|                            | `$git push`                                          |                                                                 |
| Update a local repo        | `$git pull `                                         | Or `$git fetch` and `$git merge`                                |
| Remove git connection      | `$rm -rf .git*`                                      | Check the result with `$ls -a`                                  |
| Merge branch to main       | `$git push origin HEAD:main`                         | Must be in the branch you want to merge with main               |
| Rebase branch              | `$git rebase main OR $git rebase -I origin/main`     | If `error: nothing to do`, `$git reset main`                    |
| Sink up a branch with main | `$git checkout main`, `$git pull`, `$git checkout branch_name`, `$git merge main` | Rebasing makes the commits look cleaner |
| Commit selectively         | `$git add -p`                                        | same as `--patch`                                               |
| See commit breakdown       | `$git diff`                                 | `--staged` to see breakdown, `--cached` to see what's staged |
| See commit history         | `$git log`                                           |                                                                 |
| Write a long commit message | `$git commit -v` | Gotta use those [vim commands](https://www.radford.edu/~mhtay/CPSC120/VIM_Editor_Commands.htm) |
| Add to previous commit     | `$git commit --amend`                                | After amend, gotta `$git push --force`                          |
| Cherry-pick commits        | `$git cherry-pick oldest_git_hash^..newest_git_hash` |                                                                 |
| Fix commits | `$git rebase --interactive HEAD~number_of_commits_you_want_to_fix` | Check with `$git log` after |
| Delete a local branch      | `$git branch -d branch_name`                         | To force it, use `-D` instead                                   |
| Delete a remote branch | `$git push origin --delete branch_name` | Same can be done on the web |
| View branches              | `$git branch`  |  `--remote` to view just remote-tracking branches, `--all` to view local and remote branches |
| Remove obsolte branches | `$git fetch origin --prune` |                         |
