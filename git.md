# Git Cheat Sheet

## Configuration
| Command | Description |
| - | - |
| `git config user.name <name>` | Set user name for specify repository |
| `git config user.email <email>` | Set user email for specify repository |

## Basic
| Command | Description |
| - | - |
| `git clone <repository ssh/http>` | Clone the given repository |
| `git status` | Get current state of local repository |
| `git add <file/. >` | Add file to commit. Use dot to all files |

## Commit
| Command | Description |
| - | - |
| `git commit -m <message>` | Commit using the given message |
| `git commit -a -m <message>` | Add all files and commit using the given message |
<!---

git push --set-upstream origin $new_branch

## Working with Repositories

git checkout -- $files
git checkout $branch
git checkout -b $new_branch
git branch $new_branch
git branch $new_branch $base_branch

You must be on the branch you want to merge to
git merge $branch_to_merge
--->
