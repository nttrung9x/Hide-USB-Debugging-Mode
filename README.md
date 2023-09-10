# https://www.reddit.com/r/Magisk/comments/pwaoe9/help_is_there_a_way_to_hide_adb_status_from_apps/
HA! I FOUND IT(solution)
YES!
step1- first close all applications
step2- Enable ,yes enable usb debugging(adb)
step3- run ------>settings put global adb_enabled 2------------(as root)
(in a terminal)
OR
step3-run -------->adb shell settings put global adb_enabled 2
and yes i mean it seriosly that 'settings put global adb_enabled 2' it is not a mistake
and it might not work for you


# https://github.com/redlee90/Hide-USB-Debugging-Mode
xxx
# Hide-USB-Debugging-Mode
An Xposed module that can be used to hide your device's usb debugging status. Useful for apps such as TWC/Spectrum TV which refuse to run when they detect that your usb debugging mode is on.
