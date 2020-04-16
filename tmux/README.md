Useful hotkeys for when using [tmux](https://github.com/tmux/tmux/wiki) . These are mapped mostly using [AutoHotkeys](https://www.autohotkey.com/) and the following scripts:

```
^!-::
Send, {Ctrl down}b{Ctrl up}
Send, p
return

^!=::
Send, {Ctrl down}b{Ctrl up}
Send, n
return

^#[::
Send, {Ctrl down}b{Ctrl up}
Send, :setw synchronize-panes
Send {Enter}
return

^#]::
Send, {Ctrl down}b{Ctrl up}
Send, z
return

^#\::
Send, {Ctrl down}b{Ctrl up}
Send c
return

^#0::
Send, {Ctrl down}b{Ctrl up}
Send, `%
return

^#1::
Send, {Ctrl down}b{Ctrl up}
Send, "
return

^#2::
Send, {Ctrl down}b{Ctrl up}
Send, {Ctrl down}o{Ctrl up}
return

^#3::
Send, {Ctrl down}b{Ctrl up}
Send, o
return

^#4::
Send, {Ctrl down}b{Ctrl up}
Send, d
return

^#5::
Send, {Ctrl down}b{Ctrl up}
Send, {Down}
return

^#6::
Send, {Ctrl down}b{Ctrl up}
Send, :resize-pane -L 10
Send {Enter}
return

^#7::
Send, {Ctrl down}b{Ctrl up}
Send, :resize-pane -R 10
Send {Enter}
return

^#8::
Send, {Ctrl down}b{Ctrl up}
Send, :resize-pane -U 2
Send {Enter}
return

^#9::
Send, {Ctrl down}b{Ctrl up}
Send, :resize-pane -D 2
Send {Enter}
return
```

![Stream Deck Screenshot](https://raw.githubusercontent.com/KranzSysdig/StreamDeckButtons/master/tmux/streamdeck.jpg)
