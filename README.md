# xrandrl

## Requirements

```{sh}
sudo apt-get install python3 libx11-dev libxrandr-dev
```

## Examples

```{sh}
$ xrandrl --connected
eDP2
DP2-1
DP2-2

$ xrandrl --enabled 
eDP2
DP2-2

$ xrandrl --connected --disabled
DP2-1

$ xrandrl
eDP2
DP1
DP2
DP2-1
DP2-2
DP2-3
HDMI1
HDMI2
VGA1
VIRTUAL1
eDP-1-1
DVI-D-1-1
```
