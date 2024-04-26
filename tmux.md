# Tmux

## Cli commands

| Action                 | Command                               |
| ---------------------- | ------------------------------------- |
| New session            | `tmux or tmux new`                    |
| List sessions          | `tmux list-sessions or tmux ls`       |
| Attach to open session | `tmux attach-session -t or tmux a -t` |
| Terminate a session    | `tmux kill-session -t`                |

## Tmux shortcuts

### General

| Action                | Shortcut   |
| --------------------- | ---------- |
| Deattach from session | `leader d` |
| Enter command mode    | `ledaer :` |

### Windows

| Action                   | Shortcut                 |
| ------------------------ | ------------------------ |
| Create and delete window | `leader c`/&             |
| Rename window            | `leader ,`               |
| Move window              | `leader .`               |
| Change window            | `leader <window number>` |
| Previos and next window  | `leader p/n`             |
| List window              | `leader w`               |
| Panel to window          | `leader !`               |

### Panels

| Action                                    | Command               |
| ----------------------------------------- | --------------------- |
| Create horizontal panel                   | `leader "`            |
| Create vertical panel                     | `leader %`            |
| Close panel                               | `leader x`            |
| Toggle panel layout                       | `leader <space>`      |
| Toggle panel layout with direct selection | `leader ALT+<1 to 5>` |
| Toggle panel full screen                  | `leader z`            |
| Change to panel                           | `leader <arrow keys>` |
| Show pane numbers                         | `leader q`            |
| Move to numbered panel                    | `leader q<index>`     |
| Move panel left/right                     | `leader {/}`          |

### Copy Mode

| Action                 | Command    |
| ---------------------- | ---------- |
| Enter copy mode        | `leader [` |
| Quit copy mode         | `q`        |
| Start selection        | `<space>`  |
| Copy selection         | `<enter>`  |
| Paste copied selection | `leader ]` |