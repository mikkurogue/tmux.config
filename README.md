# Tmux config
My tmux config. I'll post full install instructions soon (tm)


## Keybinds & commands

Just my list of most used commands.

- `tmux ls` show a list of tmux sessions
- `tmux kill-server` kill the tmux server and all sessions
- `ctrl b I (shift i)` reload tmux config
- `ctrl b c` create new window
- `ctrl b ctrl s` save current session
- `ctrl b ctrl r` restore previous session
- `ctrl b ,` rename current window
- `tmux rename-session` rename current session
- `tmux a -t <session name>` before starting tmux, already make it attach to a specific session name, if your session name contains spaces you must wrap it in quotes. E.g. `tmux a -t "Some Session"`

#### My recommendations:
I recommend creating your session, renaming it to something you prefer and saving the session under that name.
Then, I'd recommend creating an alias in your .bashrc, .zshrc or powershell profile with that name that fires the `tmux a -t <session name>` command to instantly always open that session.
