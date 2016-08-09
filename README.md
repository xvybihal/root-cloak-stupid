# Root Cloak Stupid

### Disclaimer
You should not use this, really. If you do, you are on your own, I am not responsible of any damage you do on your device(s) and I also do not offer support. Reporting issues is probably waste of time.


### Info
This is very stupid method, how to temporarily cloak root (su binary) in CyanogenMod 13 (C13). I had an app, that checks, if there is file called `/system/bin/su` or `/system/xbin/su` and forced to me quit if it does. I wanted to use that app, and I also wanted to keep my device rooted. So I worked around it with this little stupid hack (I am not a fan of Xposed and its modules, that's why I did this).

I have tested this for 5 minutes on Oneplus 3. Not compatible with SuperSU. Survives dirty flashing of new nightly.

### Install
Just create flashable .zip of content of root-cloak-stupid folder and flash it via TWRP.

### Usage
  - have root enabled in your CyanogenMod (developer options)
  - in terminal/shell type `rcs`
    - hint: you can use something like [$cripter](https://play.google.com/store/apps/details?id=sites.mjwhitta.scripter) and run script with `rcs` command just by tapping once.

### Uninstall
Go figure ;o)

### Problems
Do NOT reboot while root "cloaked" by this script.