# timerGrowl

Copyright(c) Kosuke Nagano <gm.charlie@gmail.com>

# What is this.
This script enables set timer from command line.

# Install
Add cloned file path to executable path of your shell.

```
export PATH=$PATH:~/Programs/shellScript/timerGrowl
```

# How to use
timerGrowl supports two way of timer expire date

## at
timer expires specifid time.

```
% timer at 10:00
```

## after
timer expires specified minutes after.

```
% timer at 10
```

# Depends on...
## growlnotify
download and install from this URL. http://growl.info/extras.php

## afplay
included in Mac OSX
## at
included in Mac OSX

* Note
for Mac OSX: need to execute following command to enable at command.

```
% sudo launchctl load -w /System/Library/LaunchDaemons/com.apple.atrun.plist
```


