Fairly self explanatory for most of these. Just make the button 'System: Text' and put in the Text with no Title.

For the TMUX left and right buttons, I use (AutoHotkey)[https://www.autohotkey.com/] on my Windows machine to program a hotkey that can do the necessary CTRL+b p, CTRL+b, n.

```^!-::
Send, {Ctrl down}b{Ctrl up}
Send, p
return```

```^!=::
Send, {Ctrl down}b{Ctrl up}
Send, n
return```

![Stream Deck Screenshot][https://raw.githubusercontent.com/KranzSysdig/StreamDeckButtons/master/Kubernetes/Screenshot.png]