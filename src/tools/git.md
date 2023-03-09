# git

<https://git-scm.com>

## Installation Resources

### macOS

```
brew install git
```

Ref: <https://formulae.brew.sh/formula/git>

## Useful Commands

| Command | Notes |
|---------|-------|
|`git add --paginate` | |
|`git add --patch` | |
|`git bisect` | <https://git-scm.com/docs/git-bisect> |
|`git blame <filename>` | |
|`git branch -m new-branch-name` | Rename the current branch to `new-branch-name` |
|`git checkout -` | Switch between your previous and current branch |
|`git cherry-pick <start-point>..<end-point>` | |
|`git commit --amend --no-edit` | |
|`git commit --amend` | |
|`git config --global init.defaultBranch <name>` | Set the defaul branch name to `<name>` |
|`git diff --cached` | |
|`git diff --stat` | |
|`git help <command>` | |
|`git log --author="jelita"` | |
|`git log --grep -E -i <search term>` | |
|`git log --oneline -- <filename>` | |
|`git log --oneline --decorate --graph --all` | |
|`git log --oneline --decorate` | |
|`git log --oneline` | |
|`git log --pretty=format:'%h - %an [%ar] %s'` | |
|`git log --show-signature` | |
|`git log -S <string>` | |
|`git rebase --interactive HEAD~3` | |
|`git rebase --onto` | |
|`git reflog` | |
|`git reset --hard HEAD~1` | |
|`git reset --soft HEAD^` | `^` means the parent (of `HEAD` in this case)|
|`git reset HEAD~` | [Discard the last commit](https://www.oreilly.com/library/view/git-pocket-guide/9781449327507/ch04.html#_discarding_the_last_commit) |
|`git restore <file>` | |
|`git show <hash>` | |
|`git show` | Show the latest changes |
|`git stash -u` | |
|`git stash apply n` | |
|`git stash list` | |
|`git stash push -- specific-file.txt` | |
|`git stash push -m "my_stash_name"` | |
|`git stash` | |
|`git status --short` | |

## Notes

- There is no `git squash` command. A "squash" is really an interactive rebase.
- Quit `vim` with `:cquit` (or `:cq` for short) to close with an error (non-0) and stop `git` from receiving a commit message (aborting the commit).

## Useful Resources

- [5 Useful Tips For A Better Commit Message](https://thoughtbot.com/blog/5-useful-tips-for-a-better-commit-message)
- [Combining Git commits with squash](https://youtu.be/V5KrD7CmO4o)
- [Deliberate Git](https://vimeo.com/72762735)
- [Git Rename Branch – How to Change a Local Branch Name](https://www.freecodecamp.org/news/git-rename-branch-how-to-change-a-local-branch-name/)
- [How can I undo the last commit?](https://www.git-tower.com/learn/git/faq/undo-last-commit)
- [How to Use git blame](https://linuxhint.com/git_blame/)
- [Mastering Git](https://thoughtbot.com/upcase/mastering-git)
- [Practical Git: Show who changed a line last with git blame](https://egghead.io/lessons/tools-practical-git-show-who-changed-a-line-last-with-git-blame)
- [Rewriting history](https://www.atlassian.com/git/tutorials/rewriting-history)
- [What is Git Blame?](https://youtu.be/UxUHyJf6Aj0)
- <https://forum.upcase.com/>
- <https://git-scm.com/doc>
- <https://gitready.com>
