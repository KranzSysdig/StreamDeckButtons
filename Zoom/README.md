Useful hotkeys for when using [Zoom](https://zoom.us/) (including muting Slack!). These are mapped using [AutoHotkeys](https://www.autohotkey.com/) and the following scripts:

```
^!j::
WinActivate, Zoom
Send, {Alt down}a{Alt up}
Send, {Alt down}{Tab}{Alt up}
return

^!k::
WinActivate, Zoom
Send, {Alt down}v{Alt up}
Send, {Alt down}{Tab}{Alt up}
return

^!l::
WinActivate, Slack
Send {Raw}/dnd 12h
Send {Enter}
Send, {Alt down}{Tab}{Alt up}
return

^!p::
WinActivate, Slack
Send {Raw}/dnd off
Send {Enter}
Send, {Alt down}{Tab}{Alt up}
return
```

![Stream Deck Screenshot](https://raw.githubusercontent.com/KranzSysdig/StreamDeckButtons/master/Zoom/Screenshot.PNG)
