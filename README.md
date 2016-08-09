# Root Cloak Stupid

### Disclaimer
You should not use this, really. If you do, you are on your own, I am not responsible on any damage you do on your device(s) and I also do not offer support. Reporting issues is probably waste of time.


### Info
This is very stupid method, how to temporarily cloak root (su binary) in CyanogenMOD 13 (C13). I had an app that checks, if there is file called `/system/bin/su` or `/system/xbin/su` and forced to quit if it does. I wanted to use that app, and also keep my device rooted. So I worked around it with this little stupid hack (I am not a fan of Xposed and its modules).

I have tested this for 5 minutes on Oneplus 3. Not compatible with SuperSU.

### Install
Just create flashable .zip of content of root-cloak-stupid folder and flash it via TWRP.

### Usage
  - have root enabled in your CyanogenMOD (developer options)
  - in terminal/shell type `rcs`
    - hint: you can use something like [$cripter](https://play.google.com/store/apps/details?id=sites.mjwhitta.scripter) and run script just by tapping

### Uninstall
Go figure ;o)

### Problems
Do NOT reboot while root "cloaked" by this script.