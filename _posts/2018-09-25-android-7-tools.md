---
layout:     post
title:      Lucky 7 new tools and plugins for Android developers & designers
date:       2018-09-25
summary:    A short list of great new tools and plugins for Android development.
categories: tools android
---

# Lucky 7 new tools and plugins for Android developers & designers

When I was writing my last article about [30 summertime Android libraries](https://medium.com/@mmbialas/30-summertime-android-libraries-and-tools-which-you-dont-want-to-miss-in-2018-fab053d69503),
I also got to know some nice new tools and plugins, which I find helpful during
my work. I would like to share them with you too. I hope you’ll enjoy it! 🔧 🔨
⚒ 🛠 ⛏ 🔩

![](https://cdn-images-1.medium.com/max/1600/1*OfD23UF6TP22htpIdMS-WQ.jpeg)
Photo by [Cesar Carlevarino Aragon](https://unsplash.com/photos/NL_DF0Klepc?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
on
[Unsplash](https://unsplash.com/search/photos/tools?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

*****

### 1. [adb-enhanced](https://github.com/ashishb/adb-enhanced)

This is a command-line interface to trigger various scenarios like screen
rotation, battery saver mode, data saver mode, doze mode, permission
grant/revocation. Examples:

 **Device configuration**

* Turn doze mode on: `adbe doze on`
* Turn mobile-data off: `adbe mobile-data off`
* Turn on battery saver: `adbe battery saver on`
* Don’t keep activities in the backgroun:d`adbe dont-keep-activities on`

**Permissions**

* Grant storage-related runtime permissions: `adbe permissions grant com.example
storage`
* Revoke storage-related runtime permissions: `adbe permissions revoke com.example
storage`

**Interacting with an app**

* Start an app: `adbe start com.example`
* Kill an app: `adbe force-stop com.example`

And many more. All of commands are available here:

### 2. [deep-clean](https://github.com/rock3r/deep-clean)

How many times did you manually clean Gradle cache? How many times have you
removed `.gradle` or `build` folders from your project, because your complex app
did not build? I have done it many times, but deep-clean is for the rescue!    
It is a Kotlin script that nukes all build caches from Gradle/Android projects.
Useful, when Gradle or the IDE let you down.

The script has been tested on macOS 🍎, but it is completely untested on Linux
🐧 and Windows 🖥️.

![](https://cdn-images-1.medium.com/max/1600/0*erV63X6-tuGN5MMB.png)

[Sebastiano Poggi](https://medium.com/@seebrock3r) just let you know, that:

> USE AT YOUR OWN RISK IN ANY CASE!

so be careful 👻

### 3. [Android drawable preview plugin](https://github.com/mistamek/Android-drawable-preview-plugin)

This is Android Studio and IntelliJ IDEA plugin that replaces default icons with
drawables previews inside project view. Pretty neat, huh? 🤙🏼

![](https://cdn-images-1.medium.com/max/1600/0*QMlV3wyzV6CVY7SZ.png)

### 4. [Android Input](https://plugins.jetbrains.com/plugin/10188-android-input)

Android Input is a IntelliJ IDEA/ Android Studio plugin which allows to type
text directly into Android device or emulator easily.

**Main features:**

* It remembers last used device, so you don’t need to select it every time you use
it.
* It also remembers last sent text, but it selects it all by default, so you can
send it or write it without touching your mouse.
* You can use enter/return key and send a text without using a mouse
* If you don’t want to send anything you can press ESC key to close the dialog.

Android Input plugin has 5 stars reviews and it was downloaded more than 2.4k
times.

### 5. [bundletool](https://github.com/google/bundletool)

This is a tool to manipulate Android App Bundles.    
Android App Bundles is an
improved way to package our apps. It lets you more easily deliver a great
experience in a smaller app size, allowing for the huge variety of Android
devices available today. You don’t need to refactor your code to start
benefiting from a smaller app
[[reference](https://developer.android.com/platform/technology/app-bundle/)].

**Main features:**

* Build an Android App Bundle from pre-compiled modules of a project.
* Generate an APK Set archive containing APKs for all possible devices.
* Extract APK(s) from the APK Set compatible with a given device.
* Install APK(s) from the APK Set compatible with a connected device.
* Extract device spec from a device as a JSON file.

### 6. [GradientDrawableTuner](https://github.com/duanhong169/GradientDrawableTuner)

Actually this is an Android application which can be used as a tool. If you were
confused about `drawables` in Android, this is the answer.    
By using this app you can understand, how the properties of `GradientDrawable` affect the
Drawable's appearance, intuitively. The `GradientDrawableTuner` also supports
generating the corresponding xml code.

![](https://cdn-images-1.medium.com/max/1600/1*-7ucTzvPIWU_vJ4iKVhTGg.png)

**Features:**

* Almost all of the `<shape>`'s properties can be tuned.
* Generating the xml code which can build the `<shape>` you just crafted.

The app is open-sourced and released under Apache 2.0 license.

### 7. [ColorBox](https://www.colorbox.io/)

This is a tool for designers but also for developers who have hands on improving
UI or they also design applications.    
It is Lyft’s color algorithm that they used to create their accessible color system.    
You can use that if you want
to boost / improve UI in your app or generate a brand new color palette with
colors that match each other. 🎨

![](https://cdn-images-1.medium.com/max/1600/1*WmSrU-0sM3RRkk4SwJe96g.png)

You can find also a really nice article about the tool with all the explanations
[here](https://design.lyft.com/re-approaching-color-9e604ba22c88).

*****

You can also check my other articles that have been released earlier this year:

* [30 summertime Android libraries and tools which you don’t want to miss in
2018](https://medium.com/@mmbialas/30-summertime-android-libraries-and-tools-which-you-dont-want-to-miss-in-2018-fab053d69503)
* [25 new Android libraries, projects and tools worthy to check in Spring
2018](https://medium.com/@mmbialas/25-new-android-libraries-projects-and-tools-worthy-to-check-in-spring-2018-68e3c5e93568)
* [25 new Android libraries and projects to check at the beginning of
2018](https://proandroiddev.com/25-new-android-libraries-and-projects-to-check-at-the-beginning-of-2018-ba3b422bbbb4)

To be notified about my new articles and stories, follow me on
[Medium](https://medium.com/@mmbialas) and
[Twitter](https://twitter.com/mmbialas). You can find me on
[LinkedIn](https://www.linkedin.com/in/mmbialas) as well. Cheers!
