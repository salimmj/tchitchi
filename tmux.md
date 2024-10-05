# tmux Cheat Sheet

## Sessions
- Create new session:  
  `tmux new -s session-name`

- List sessions:  
  `tmux ls`

- Attach to session:  
  `tmux attach -t session-name`

- Detach from session:  
  `Ctrl + b` → `d`

- Kill session:  
  `tmux kill-session -t session-name`

## Windows
- New window:  
  `Ctrl + b` → `c`

- Switch windows:  
  - Next: `Ctrl + b` → `n`
  - Previous: `Ctrl + b` → `p`
  - List: `Ctrl + b` → `w`

- Rename window:  
  `Ctrl + b` → `,`

## Panes
- Split pane (vertical):  
  `Ctrl + b` → `"`

- Split pane (horizontal):  
  `Ctrl + b` → `%`

- Switch between panes:  
  `Ctrl + b` → Arrow keys

- Resize pane:  
  `Ctrl + b` → `Ctrl + Arrow`

- Close pane:  
  `Ctrl + d`

## Other Commands
- Command prompt:  
  `Ctrl + b` → `:`

- Attach session:  
  `tmux attach -t session-name`
