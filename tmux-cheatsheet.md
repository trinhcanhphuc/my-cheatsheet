# TMUS SHORTCUTS AND CHEATSHEET

## Install
Follow homepage:
    

## Run
### Create new session without or with name

    $ tmux
    or
    $ tmux new -s [session_name]

### Attach session without or with name

    $ tmux a
    or
    $ tmux a -t [session_name]


### List sessions:

    $ tmux ls

### Kill one or all session:

    $ tmux kill-session -t [session_name]
    or
    $ tmux kill-session -a


## Hot keys
In tmux, hot kes prefix is `Ctrl + b`. Example `Ctrl + b + d` to detach current session

### Windows

    c   create window
    w   list windows
    n   next window
    p   previous window
    f   find window
    ,   name window
    &   kill window
    d   detach current session

## Panes (split)

    %   vertical split
    "   horizontal split
    o   swap panes
    q   show pane numbers
    x   kill pane
    ⍽  space - toggle between layouts
    <prefix> q (Show pane numbers, when the numbers show up type the key to goto that pane)
    <prefix> { (Move the current pane left)
    <prefix> } (Move the current pane right)
    <prefix> z toggle pane zoom
