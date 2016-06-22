---
layout:     post
title:      Helpful ADB commands
date:       2016-06-23
summary:    A post just to memorise many useful ADB commands.
categories: tools adb
---

Several weeks ago I started to play with a prototype of Intel Internet of Things device for
gathering information from vehicles using an OBD port [^1]. What is really interesting,
the device works on an Android OS (first prototype used Android 5.1.1 Lollipop and then
I updated it with Android 6.0.1 Marshmallow). The device doesn't have a screen, so it is
vital to know all useful ADB commands by heart (or use that blog post as a reference 😇).

## ADB general commands

#### adb +

`start-server` - starts an ADB daemon.  
`kill-server` - kills the ADB daemon.  
`devices` - shows the list of plugged in devices (you can also use `adb devices -l`).  
`pull {path_to_file.apk} {path_to_save}` - fetches an app from the system.  
`push {path_to_file.apk} {path_to_save}` - sends the app to the system, e.g. `add push <apk file> /system/app`.    
`install {path_to_file.apk}` - installs an apk from a specific path (if you plug in more than one device, you need to
  indicate where you want to install the apk with `-s` parameter: `adb -s {deviceIDfromList} install {path_to_file.apk`).  
`uninstall "package.name"` - uninstalls the app using the app's package. You can also apply `-s` parameter to determine a device.  
`remount` - remounts the /system, /vendor (if present) and /oem (if present) partitions on the device read-write - you can use that when write permissions are not set.  
`shell` - gives an access to the shell.  
`logcat` - logs all events from a device. You can save logs to file using `-s` parameter: `adb logcat -s TAG_OF_THE_CLASS > "YourLogs.txt"`  
**`help` - cheatsheet of almost every command you will need.**  


## ADB shell commands

#### adb shell +

`getprop ro.build.version.release` - shows the version of Android system.  
`dumpsys battery | grep level` - battery level.  
`dumpsys package com.PackageName.enterprise` - dumps app permission state.

`pm list packages -f` - shows a list of packages / applications installed in the system.  
`pm list packages -f | cut -f 2 -d "="` - lists all installed apps.
`pm list packages | awk -F ":" '{print $2}'` - the same as above.  

`am start -n com.package.name/com.package.name.ActivityName` - starts an Activity pointed by you (in the same manner you can run an Android Service).  

`pm list permissions -d -g` - list permissions and status by group.  
`pm [grant|revoke] <permission-name>` - grant or revoke one or more permissions, for example: `adb shell pm revoke com.PackageName.enterprise android.permission.READ_CONTACTS`  

**Basic operations with Android Settings:**    

`am start -a android.bluetooth.adapter.action.REQUEST_ENABLE` - turns on Bluetooth.  
`am start -n com.android.settings/.wifi.WifiSettings` - opens WiFi.   
`am start -n com.android.settings/.wifi.WifiInfo` - fetches WiFi info.  
`am start -n com.android.settings/.wifi.WifiStatusTest` - shows WiFi status.  
`am start -n com.android.settings/.LanguageSettings` - opens language settings.  
`am start -n com.android.settings/.DevelopmentSettings` - opens development options.  
`am start -n com.android.settings/.DateTimeSettingsSetupWizard` - sets up Date / Time.  

As **root** using service call:  
`su -c service call bluetooth_manager 6 turn bluetooth on` - turns on Bluetooth.
`su -c service call bluetooth_manager 8 turn bluetooth off` - turns off Bluetooth.  

As **non-root** using **key events**:  
`am start -a android.settings.BLUETOOTH_SETTINGS` - opens Bluetooth settings.  
`input keyevent 19` - a key event for *up* button.   
`input keyevent 23` - a key event for *enter / return* (Dpad center).       


## Useful links
1. [What's the Android ADB shell “dumpsys” tool and what are its benefits?](http://stackoverflow.com/questions/11201659/whats-the-android-adb-shell-dumpsys-tool-and-what-are-its-benefits)
2. [https://developer.android.com/studio/command-line/adb.html](https://developer.android.com/studio/command-line/adb.html)
3. [https://developer.android.com/studio/command-line/shell.html](https://developer.android.com/studio/command-line/shell.html)
4. [Gist - list all installed packages in android adb shell](https://gist.github.com/davidnunez/1404789)

---
[^1]: I think I will post a little bit more about the device in the future, as it is really interesting.
