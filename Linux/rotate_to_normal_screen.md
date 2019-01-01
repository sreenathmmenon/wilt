Type following command to rotate the screen back to it's normal (landscape) layout.

Command = xrandr -o normal

## Similar Implementations:

```
$ xrandr
Screen 0: minimum 320 x 200, current 640 x 512, maximum 8192 x 8192
eDP-1 connected primary 640x512+0+0 (normal left inverted right x axis y axis) 344mm x 193mm
   1920x1080     60.01 +  60.01    59.97    59.96    59.93    40.00  
   1680x1050     59.95    59.88  
   1600x1024     60.17  
   1400x1050     59.98  
   1600x900      59.99    59.94    59.95    59.82  
   1280x1024     60.02  
   1440x900      59.89  
   1400x900      59.96    59.88  
   1280x960      60.00  
   1440x810      60.00    59.97  
   1368x768      59.88    59.85  
   1360x768      59.80    59.96  
   1280x800      59.99    59.97    59.81    59.91  
   1152x864      60.00  
   1280x720      60.00    59.99    59.86 
```

```
$ xrandr -s 1280x1024
$ xrandr -s 1920x1080
```

#### References:

* https://wiki.archlinux.org/index.php/xrandr
* https://xorg-team.pages.debian.net/xorg/howto/use-xrandr.html
