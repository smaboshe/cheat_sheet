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
|`git add --patch` | |
|`git blame <filename>` | |
|`git cherry-pick <start-point>..<end-point>` | |
|`git commit --amend --no-edit` | |
|`git commit --amend` | |
|`git diff --cached` | |
|`git help <alias>` | |
|`git log --grep -E -i <search term>` | |
|`git log --oneline -- <filename>` | |
|`git log --oneline --decorate --graph --all` | |
|`git log --oneline --decorate` | |
|`git log --oneline` | |
|`git log --pretty=format:'%h - %an [%ar] %s'` | |
|`git log -S <string>` | |
|`git rebase --interactive HEAD~3` | |
|`git reflog` | |
|`git reset --hard HEAD~1` | |
|`git reset --soft HEAD^` | `^` means the parent (of `HEAD` in this case)|
|`git restore <file>` | |
|`git show <hash>` | |
|`git show` | |
|`git stash -u` | |
|`git stash` | |
|`git status --short` | |

## Notes

- There is no `git squash` command. A "squash" is really an interactive rebase.
- Quit `vim` with `:cquit` (or `:cq` for short) to close with an error (non-0) and stop `git` from receiving a commit message (aborting the commit).

## Useful Resources

- [5 Useful Tips For A Better Commit Message](https://thoughtbot.com/blog/5-useful-tips-for-a-better-commit-message)
- [Combining Git commits with squash](https://youtu.be/V5KrD7CmO4o)
- [Deliberate Git](https://vimeo.com/72762735)
- [How can I undo the last commit?](https://www.git-tower.com/learn/git/faq/undo-last-commit)
- [How to Use git blame](https://linuxhint.com/git_blame/)
- [Mastering Git](https://thoughtbot.com/upcase/mastering-git)
- [Practical Git: Show who changed a line last with git blame](https://egghead.io/lessons/tools-practical-git-show-who-changed-a-line-last-with-git-blame)
- [Rewriting history](https://www.atlassian.com/git/tutorials/rewriting-history)
- [What is Git Blame?](https://youtu.be/UxUHyJf6Aj0)
- <https://git-scm.com/doc>
