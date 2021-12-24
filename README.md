# dwm
A build for [dynamic window manager by suckless](http://dwm.suckless.org)

# Theming
To change themes, edit the config.h file's include headers.
```
- #include "dwmthemes/current_theme.h"
+ #include "dwmthemes/new_theme.h"
```

Then build and install dwm.
```
sudo make clean install
```
