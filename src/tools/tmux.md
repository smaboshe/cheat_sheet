# tmux

<https://tmux.github.io>

## Installation Resources

### macOS

```
brew install tmux
```

Ref: <https://formulae.brew.sh/formula/tmux>

## Useful Commands

| Command | Notes |
|---------|-------|
| `tmux list-commands` | |
| `tmux list-keys` | |
| `tmux list-sessions` | |
| `tmux ls` | |
| `tmux new-session -s <session-name>` | |
| `tmux switch-client -t <session-name>` | |
| `tmux` | |

### Window Management

| Command | Notes |
|---------|-------|
| `C-b "` | Horizontal window split |
| `C-b %` | Vertical window split |
| `C-b d` | Detach from the current session |
| `C-b L` | Toggle between `tmux` sessions |

## Notes

- `tmux` uses `sessions`, `windows` and `panes`
- To customise `tmux` create `~/.tmux.conf` and add customisations there

## Useful Resources

- [A Quick and Easy Guide to tmux](https://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/)
- [Making tmux Pretty and Usable - A Guide to Customizing your tmux.conf](https://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/)
- [tmux](https://thoughtbot.com/upcase/tmux)
- <https://thoughtbot.com/blog/tags/tmux>
