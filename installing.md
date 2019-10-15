# Installation

### There are 2 methods to install - manual or scripted

## Simple method

If you want to host on a **Linux computer**, a **Mac** or an **Android** phone, paste this command into Termux (an app on the Play Store) or a terminal:
```
(. <($(which curl>/dev/null&&echo curl -Ls||echo wget -qO-) https://git.io/JeOXn))
```

If you want to host on **Windows** (7 and higher) paste this command into [Windows Powershell](http://www.powertheshell.com/topic/learnpowershell/firststeps/console):
```
iex (New-Object Net.WebClient).DownloadString("https://git.io/JeOX4")
```
Or for Heroku on **Windows**:
```
iex (New-Object Net.WebClient).DownloadString("https://git.io/Je8b0")
```

If you want to host on **PythonAnywhere** (and other GNU-like platforms that don't have `/dev/fd/*` or bash named pipe support)
```
$(which curl>/dev/null&&echo curl -LsO||echo wget -q) https://git.io/JeOXn&&(. JeOXn);rm JeOXn
```

## Advanced method

[Click Here](installing_advanced "Advanced installation")
