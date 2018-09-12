---
layout:     post
title:      10 tools which will boost your Android productivity and hype
date:       2017-02-01
summary:    A short list of great tools which increase your performance and efficiency during daily Android development.
categories: tools android
---

The main purpose of this post is to list and describe tools (mainly **free** ones), which allow you to
boost your productivity, efficiency and increase hype among your product owners and managers.
To every single tool (or groups of tools) I will add annotations like: **[FREE]** or **[FREE/PAID]** or **[PAID]**.
Let's not waste time and begin!

1. [Android Tool for Mac](https://github.com/mortenjust/androidtool-mac) **[FREE]** -- when I discovered this tool, it just made my day.  
It is completely free and allows you to:
  * Record screen videos,
  * take screenshots,
  * install (sideload) APKs,
  * take bug reports,
  * use common scripts.  

   You can see the main menu in the picture below. You can simply take a screenshot or start recording a video, by clicking on a proper icon.

    ![AndroidToolMenu](/images/2017/android_tools/androidtool_menu.png)

    The tool offers also quite powerful preferences which you can see below:

    ![AndroidToolPreferences](/images/2017/android_tools/androidtool_preferences.png)

    What is really important to me, it can also **create a gif** for you, besides mp4 format.
    You can set the quality of videos and gifs and adapt **Status Bar** to the needs of the video or screenshot.

    One of disadvantages is that the **Android tool is available only for OSX / MacOS.**

    Also, taking bug reports is quite limited. If you want to improve an experience of this action, especially for your users and product teams, you should consider some different tool. One of the best is [Instabug](https://instabug.com/) which offers lots of great tools, like e.g.
      * In-App Feedback
      * Screenshot Attachment
      * Environment Snapshot
      * In-App Surveys
      * Feature Request

    I think, it is really worthy to try it and pay small subscription price. Companies like SoundCloud, Samsung, PayPal, Lyft and Yahoo! can not be wrong.    
    What is also important, you have an access to the crash reporting console which can be easily a replacement to well-known [Crashlytics](https://fabric.io/kits/android/crashlytics) and this is a reason, why I recommend it.


2. [Vysor](https://www.vysor.io/) **[FREE/PAID]** -- this is a Chrome app[^1], compatible with all operating systems. It gives
you a possibility, to operate your physical device from your desktop.  

    ![VysorMovie](/images/2017/android_tools/vysor_movie.gif)

    As per above gif, you can use a mouse pointer to click and scroll in the device. Computer keyboard would also work.
    There are two versions of the app:

      * Free - it offers mirroring and controlling your Android device and taking screenshots.
      * Pro - it gives you high quality mirroring, taking screen videos, fullscreen mode, going wireless and drag & drop functionality.

    Honestly speaking, **combination of the Android Tool for Mac and Vysor Free, covers most of the cases of usage**. You can do a live demo,
    you can take screen video and share it after, or record a gif. However, for sake of having a really good quality of streaming / mirroring,
    I think it is worthy to go Pro, especially that it costs 1.99$/mo.

    To sum up, **use these two apps and make your demo perfect!** It will make your stakeholders happy as well! :smile:

3. [Genymotion](https://www.genymotion.com/) **[PAID]** -- I think everybody knows Genymotion. If not, this is a powerful Android emulator.

     ![Genymotion](/images/2017/android_tools/genymotion.png)

     Genymotion

      > is an AOSP, ported to VirtualBox (by integrating its drivers). It is compiled directly in x86. So it can run directly on your CPU/GPU without any abstraction or translation. It makes a huge difference in term of performances.[^2]

      The tool offers:

      * Compatibility with Android SDK tools, Eclipse and Android Studio (there is also a plugin which I listed in my last article about [Android Studio tips & tricks](http://mmbs.github.io/tools/ide/2016/11/07/android-studio-tips-tricks/)),
      * lots of predefined emulators,
      * using laptop webcam as the video source for your Android camera,
      * testing your app with various charge levels and see how it handles those use cases,
      * using the GPS widget to test your geolocation-based apps,
      * running UI tests like e.g. Espresso,
      * screencasting (taking screenshots, recordings etc.).

      In addition, you can install Google Services applications, like Goole Play Store and enjoy the full Android experience.

      Unfortunately, every rose has its thorns and **Genymotion is an extra-paid solution** (just think about all these features, which I listed above). The [cheapest plan](https://www.genymotion.com/pricing-and-licensing/) costs 99€/year.

      Update 4th Feb 2017: **Genymotion is also available for free**, but for personal use. You can download it [here](https://www.genymotion.com/fun-zone/).

      **Another [FREE] alternative** is to use built-in [Android emulator](https://developer.android.com/studio/run/emulator.html). Since 2015 it works pretty well, as it uses Google Intel x86 images. I like its smoothness, intuitiveness and that it is well-integrated with Android Studio.  

4. [Postman](https://www.getpostman.com/) **[FREE/PAID]** -- this tools is just **awesome**. I use it for 3 years now, initially as a Google Chrome extension, then as a native app. Postman helps you to be as productive and efficient as possible, while working with APIs.

    ![Postman](/images/2017/android_tools/postman_collections.jpg)

    Basic features include [^3]:

    * Compact layout,
    * HTTP requests with file upload support,
    * formatted API responses for JSON and XML,
    * HATEOAS support,
    * image previews,
    * request history,
    * basic Auth and OAuth 1.0 / 2.0 helpers,
    * autocomplete for URL and header values,
    * key/value editors for adding parameters or header values. Works for URL parameters too,
    * using environment variables to easily shift between settings. Great for testing production, staging or local setups,
    * keyboard shortcuts to maximize your productivity,
    * using collections to organize requests,
    * documenting requests inside collections. You can even store entire HTML notes. Postman uses Bootstrap so you can use it too to style your notes,
    * downloading and share collections with your team of developers.

    What I really like about Postman, is:

    * The ability to write pre-request scripts (e.g. for generating and passing timestamps) and then play with results (write tests or save results for another API call),
    * having multiple environments (dev, stage / preprod, prod etc.),
    * grouping API calls in collections,
    * syncing collections across the team (you can achieve it *manually* by exporting the collection or *buy* a PRO version to sync it across all teammates automatically),
    * great documentation.

    For me the free version is enough, but You can of course read more about product comparison and pricing plans on the [official website](https://www.getpostman.com/products).

5. [Sequel Pro](https://www.sequelpro.com/) **[FREE]** -- a fast and easy-to-use Mac database management application for working with MySQL databases. You can check it on [Github](https://github.com/sequelpro/sequelpro). Main reasons, why I like it:

    * Quick and direct access to MySQL Databases on local and remote servers,
    * it is a native app,
    * good documentation,
    * open-source project.

    ![SequelPro](/images/2017/android_tools/sequel_pro.png)

   Unfortunately, there is only OSX / MacOS version available for now. Still, [MySQL Workbench](https://www.mysql.com/products/workbench/) might be considered as a free Windows alternative.

   If you use PostgreSQL, you can use PSequel, which provides a clean and simple interface to perform common PostgreSQL tasks and it is free.

6. [JD-GUI](http://jd.benow.ca/) **[FREE]** -- it is a standalone graphical utility that displays Java source codes of `.class` files. You can browse the reconstructed source code and for instance, access to methods and fields. I always use it when I decompile Android apps.

    ![JD-GUI](/images/2017/android_tools/jd-gui.png)

    The tool is open-source and the code is available on [Github](https://github.com/java-decompiler). There are also 2 plugins to use with:

     * [IntelliJ](https://plugins.jetbrains.com/idea/plugin/7100-java-decompiler-intellij-plugin) (last changes: 28 March 2014),
     * [Eclipse](https://github.com/java-decompiler/jd-eclipse) (last changes: 23 April 2015).

7. [Android Asset Studio](https://romannurik.github.io/AndroidAssetStudio/) **[FREE]** -- who didn't hear about Roman Nurik? His contributions to the Android world are just exceptional. One of them is Android Asset Studio which is

    > A web-based set of tools for generating graphics and other assets that would eventually be in an Android application's res/ directory.

    The set is available on [Github](https://github.com/romannurik/AndroidAssetStudio) and consists of:

    * [Launcher icon generator](https://romannurik.github.io/AndroidAssetStudio/icons-launcher.html)
    * [App shortcut icon generator](https://romannurik.github.io/AndroidAssetStudio/icons-app-shortcut.html)
    * [Notification icon generator](https://romannurik.github.io/AndroidAssetStudio/icons-notification.html)
    * [Simple nine-patch generator](https://romannurik.github.io/AndroidAssetStudio/nine-patches.html)
    * [Generic icon generator](https://romannurik.github.io/AndroidAssetStudio/icons-generic.html)
    * [Action bar / tab icon generator](https://romannurik.github.io/AndroidAssetStudio/icons-actionbar.html)
    * [Launcher icon animator](https://romannurik.github.io/AndroidIconAnimator/)

8. [Material Colors for Mac](https://github.com/romannurik/MaterialColorsApp) **[FREE]**-- another cool tool from Roman Nurik. This is a Material Colors palette viewer accessible from Menu Bar. You can download it from [here](https://github.com/romannurik/MaterialColorsApp/releases/download/v1.1.0/MaterialColors-1.1.0.zip). The only disadvantage is that, Windows users can not use it. You can check, how it works below:

    ![MaterialColors](/images/2017/android_tools/material-colors.png)

9. [Spectacle](https://www.spectacleapp.com/) **[FREE]** -- this is a tool for Mac users, who struggle with lack of move / resize / operate functionality of windows, which we know well from Microsoft Windows.

    ![Spectacle](/images/2017/android_tools/spectacle.gif)

   **[PAID]** alternative of my choice is [Moom](https://manytricks.com/moom/) I use it on a regular basis. It costs 10$ and I consider it as more powerful solution.

10. [f.lux](https://justgetflux.com/) **[FREE]** -- tool that makes the color of your computer's display adapt to the time of a day. It is warm at night and looks like sunlight during the day. If you work at night, the tool will do the job! I use it everyday. It helps to stake awake, even after working until late hours. What is more, I noticed that I wake up more relaxed. What I like most about f.lux:

    * Useful preferences with 4 presets for your needs (as you can see, I use `Working late` preset):

        ![f.lux_preferences](/images/2017/android_tools/f.lux_preferences.png)

    * Notifications:

        ![f.lux_notification](/images/2017/android_tools/f.lux_notification.png)

    * It allows me sleep well.

---
That was the very last point! I hope you enjoyed the article. Please let me know, if you know any useful tool which boosts your Android productivity!

If you like my article, please don't forget to go to Medium and click ❤ to recommend it to others! Also, follow me on Medium and Twitter! Cheers!


---
[^1]: Actually you can also install Vysor which is wrapped into a native app. The link is [here](https://plus.google.com/110558071969009568835/posts/Ub7QKu2Pddu).
[^2]: [How does AndroVM/GenyMotion work?](https://www.quora.com/How-does-AndroVM-GenyMotion-work)
[^3]: [Source](https://github.com/postmanlabs/postman-app-support/wiki)
