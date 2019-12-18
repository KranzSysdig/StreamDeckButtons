I do a lot of online demos, so I'm a big fan of (Epic Pen)[https://epic-pen.com/]. It allows me to do screen annotations across both slides and product demos, so really useful. Most Epic Pen actions have hotkeys already, so it's just a case of mapping these in Stream Deck. For colour changing, I have the following, which maps to Blue, Red/Pink, Yellow, Black:

```
^!1::
WinActivate, Epic Pen
MouseClick, left, 825, 595
Send, {Alt down}{Tab}{Alt up}
return

^!2::
WinActivate, Epic Pen
MouseClick, left, 825, 620
Send, {Alt down}{Tab}{Alt up}
return

^!3::
WinActivate, Epic Pen
MouseClick, left, 850, 595
Send, {Alt down}{Tab}{Alt up}
return

^!4::
WinActivate, Epic Pen
MouseClick, left, 850, 620
Send, {Alt down}{Tab}{Alt up}
return
```

![Stream Deck Screenshot](https://raw.githubusercontent.com/KranzSysdig/StreamDeckButtons/master/Epic%20Pen/Screenshot.PNG)
