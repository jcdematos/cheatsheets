# Git Cheat Sheet

## Configuration
| Command | Description |
| - | - |
| `git config user.name <name>` | Set user name for specify repository |
| `git config user.email <email>` | Set user email for specify repository |

## Basic
| Command | Description |
| - | - |
| `git clone <repository>` | Clone the given repository |
| `git status` | Get current state of local repository |

## Commit
| Command | Description |
| - | - |
| `git add <file>` | Stage files. Use dot to add all files |
| `git checkout -- <files>` | Remove files from staged |
| `git commit -m <message>` | Commit using the given message |
| `git commit -a -m <message>` | Add all files and commit using the given message |

## Branches 
| Command | Description |
| - | - |
| `git checkout <branch>` | Change to the brach |
| `git checkout -b <new_branch>` | Create new branch and change to it |
| `git branch <new_branch>` | Create new branch from current |
| `git branch <new_branch> <base_branch>` | Create new branch from base branch |
| `git push --set-upstream origin <new_branch>` | Set new branch with upstream |

<!---

## Working with Repositories

git checkout $branch
git checkout -b $new_branch

You must be on the branch you want to merge to
git merge $branch_to_merge
--->
