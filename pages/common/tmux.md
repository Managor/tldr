# tmux

> Terminal multiplexer.
> It allows multiple sessions with windows, panes, and more.
> See also: `zellij`, `screen`.
> More information: <https://github.com/tmux/tmux>.

- Start a new session:

`tmux`

- Start a new named session:

`tmux new -s {{name}}`

- List existing sessions:

`tmux ls`

- Attach to the most recently used session:

`tmux attach`

- Detach from the current session (inside a tmux session):

`<Ctrl b><d>`

- Create a new window (inside a tmux session):

`<Ctrl b><c>`

- Switch between sessions and windows (inside a tmux session):

`<Ctrl b><w>`

- Kill a session by name:

`tmux kill-session -t {{name}}`
