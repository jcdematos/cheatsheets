# Git Cheat Sheet

## Configuration
| Command                         | Description                           |
| -                               | -                                     |
| `git config user.name <name>`   | Set user name for specify repository  |
| `git config user.email <email>` | Set user email for specify repository |

## Basic
| Command                  | Description                                   |
| -                        | -                                             |
| `git init`               | Start repository                              |
| `git clone <repository>` | Clone the given repository                    |
| `git status`             | Get current state of local repository         |
| `git log`                | Show commit history                           |
| `git pull`               | Update local with remote                      |
| `git pull --rebase`      | Update local with remote and rebase           |
| `git push`               | Push your changes to remote                   |
| `git push --force`       | Use to force changes already commit in remote |
| `

## Commit
| Command                      | Description                                      |
| -                            | -                                                |
| `git add <file>`             | Stage files. Use dot to add all files            |
| `git checkout -- <files>`    | Remove files from staged                         |
| `git commit -m <message>`    | Commit using the given message                   |
| `git commit -a -m <message>` | Add all files and commit using the given message |
| `git commit --amend`         | Merge changes into last commit                   |
| `git reset HEAD~n`           | Remove the commit but leave changes (soft reset) |
| `git reset --hard HEAD~n`    | Reset n commits and remove changes               |
| `git rever <commit_hash>`    | Revert a commit                                  |

## Branches 
| Command                                       | Description                        |
| -                                             | -                                  |
| `git checkout <branch>`                       | Change to the brach                |
| `git checkout -b <new_branch>`                | Create new branch and change to it |
| `git branch <new_branch>`                     | Create new branch from current     |
| `git branch <new_branch> <base_branch>`       | Create new branch from base branch |
| `git push --set-upstream origin <new_branch>` | Set new branch with upstream       |
| `git merge <branch_to_merge>			| Merge branch into current branch   |

## Stash
| Command                     | Description             |
| -                           | -                       |
| `git stash`                 | Stash changes           |
| `git stash list`            | List stashed changes    |
| `git stash pop`             | Apply most recent stash |
| `git stash apply`           | Apply most recent stash |
| `git stash apply stash@{n}` | Apply an older stash    |


<!---
You must be on the branch you want to merge to
git merge $branch_to_merge
--->
