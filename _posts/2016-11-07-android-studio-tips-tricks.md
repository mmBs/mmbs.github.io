---
layout:     post
title:      50 Android Studio Tips, Tricks & Resources you should be familiar with.
date:       2016-11-07
summary:    This is a cheatsheet of useful Android Studio tips, tricks, shortcuts and resources.
categories: tools ide
---

The reason of that article is to list helpful tips, tricks, shortcuts and resources for Android Studio
to improve your overall efficiency and performance. There are obviously many many more optimizations, shortcuts etc.,
but for sake of keeping this article short, I limited it to a sum of 50 points. Hope you will enjoy it!

## Visual

1. Material Colors theme for Android Logcat  

    ![Material Colors Logcat](/images/material_logcat.png)

    To change Android Studio Logcat you need to go to:  
    `Preferences (Settings on Windows / Linux machines) --> Editor —-> Colors & Fonts -—> Android Logcat`  
    and change the foreground color for every type of log.   

    My material colors

    Assert | `#BA68C8`
    Debug | `#2196F3`
    Error | `#F44336`
    Info | `#4CAF50`
    Verbose | `#BBBBBB`
    Warning | `#FF9800`


2. Prevent Android Studio Logcat from clearing the log for the current application when it crashes.  
    To do that you need to go to `Android Monitor` panel and choose `Edit filter configuration` on the right side dropdown.

    ![Preserving Logcat](/images/logcat_save.gif)

3. Apply a proper code style to your IDE (IntelliJ / Android Studio).
    Go to `Preferences --> Code Style --> Java` and in a `Scheme` dropdown you can choose your code style (or set up a new one).
    2 styles which are worth to mention:
    - [Square Java Code Styles - with Android](https://github.com/square/java-code-styles)
    - [Google Java Code Style](https://github.com/google/styleguide/blob/gh-pages/intellij-java-google-style.xml). You can import the theme as shown on the gif below:

    ![Importing Google code style](/images/codestyle.gif)

4. Use split screen for increasing efficiency.

    ![Split screen view](/images/split_screen_view.png)

    To turn this feature on, you need to right mouse click on the tab of your main screen and choose Split Vertically / Horizontally feature.

    ![Split screen view turn on](/images/split_screen_turn_on.png)

    But to be as efficient as possible we need to set up a custom keyboard's shortcut. To do that go to `Preferences --> Keymap` and search for `Split Vertically`. Then open a context menu and click `Add Keyboard Shortcut`. In my case, for vertical split view I added `control` + `alt` + `v`. It is shown on a gif below. You can define the shortcut for a horizontal split view as well.

    ![Split screen view keyboard shortcut](/images/split_view.gif)

5. Distraction Free Mode. You can enable it by going to: `View --> Enter Distraction Free Mode`

    ![Enter distraction free mode](/images/distraction_free_mode.png)

    > In the distraction-free mode, the editor occupies the entire IntelliJ IDEA frame, without any editor tabs and tool-window buttons. The code is center-aligned.[^1]

6. Use Live Templates

    - you can use a shortcut: `cmd` + `j` (Windows / Linux: `ctrl` + `j`)

    ![cmdj](/images/cmdj.gif)

    - you can use many already defined templates, like for `Toasts` or `if` conditions.

    ![toast](/images/toast.gif)

    ![ifn](/images/ifn.gif)

    - you can use your own custom templates. [Here](https://medium.com/google-developers/writing-more-code-by-writing-less-code-with-android-studio-live-templates-244f648d17c7#.vifxrypd1)
    is a great reference article by Reto Meier. You can also refer to the [IntelliJ IDEA documentation](https://www.jetbrains.com/help/idea/2016.2/live-templates.html).

## Shortcuts and helpful commands

0. The best and the most helpful command **Search for command**: `cmd` + `shift` +  `a` (Windows / Linux: `ctrl` + `shift` + `a`).  

    Let's say you want to close current tab and you don't know how. You just type: `close` and you will get a proper shortcut / command.

1. Choose from the last copy / pastes (manage your clipboard): `cmd` + `shift` + `v` (Windows / Linux: `ctrl` + `shift` + `v`).   
    By default there are 5 last copy/paste items.

    ![Choose Content to Paste](/images/content_to_paste.png)

    > The depth of the Clipboard stack is configured in the Limits section on the Editor page of the Settings dialog box. When the specified number is exceeded, the oldest entry is removed from the list.[^2]

2. Enable multicursor feature: `control` + `g` (`alt` + `j` for Windows / Linux).

    ![Multicursor](/images/ctrlg.gif)

    A [detailed article](https://android.jlelse.eu/ctrl-g-d94c88cd4475#.ed3x7e91n) about this feature is provided by Bartosz Lipinski on Medium. Highly recommended!

3. Open a class: `cmd` + `o` (Windows / Linux: `ctrl` + `n`).

4. Open any file: `cmd` + `shift` + `o` (Windows / Linux: `ctrl` + `shift` + `n`).

5. Open symbol: `cmd` + `option` + `o` (Windows / Linux: `alt` + `shift` + `n`).

6. Go to implementation: `cmd` + `option` + `b` (Windows / Linux: `ctrl` + `shift` + `b`).  
    Let's say you have an interface. By clicking on the interface name
    and then clicking the `Go to implementation` shortcut, you will be redirected to classes which implement that interface.

7. Go to declaration: `cmd` + `b` (Windows / Linux: `ctrl` + `b`).  
    It allows you to quickly check and go to a declaration of a class, method or a variable.

8. Go to type declaration: `control` + `shift` + `b` (Windows / Linux: `control` + `shift` + `b`).  
    Let's say you defined:

        Employee employee = new Employee("Michal");

    When your caret is on `employee` and you click the shortcut, you will be redirected to the `Employee` class.

9. Go to super: `cmd` + `u` (Windows / Linux: `ctrl` + `u`).  
    Let's say you override some method. When your caret in on the method's name, and you click `Goto super` shortcut,
    you will be redirected to the parent method.

10. Move between tabs: `cmd` + `shift` + `[` (move left) or `cmd` + `shift` + `]` (move right).

11. Move between Design / Text tabs in layout's view: `control` + `shift` + &larr; or `control` + `shift` + &rarr;

12. Close a current tab: `cmd` + 'w' (Windows / Linux: `ctrl` + `shift` + `a`)

13. Hide all Windows / Linux: `cmd` + `shift` + `F12` (Windows / Linux: `ctrl` + `shift` + `F12`).

14. Minimize Android Studio instance: `cmd` + `m` (Windows / Linux: `ctrl` + `m`).

15. Format your code `cmd` + `option` + `l` (Windows / Linux: `ctrl` + `alt` + `l`).

16. Auto-indent lines: `control` + `option` + `i` (Windows / Linux: `ctrl` + `alt` + `i`).

17. Implement methods: `control` + `i` (Windows / Linux: `ctrl` + `i`).  
    Let's say you implement an interface. Then, you can quickly import all methods provided by that interface just by clicking this shortcut.

18. Smart code completion (filters the list of methods and variables by expected type): `control` + `shift` + `space` (Windows / Linux:	`ctrl` + `shift` + `space`).

19. Find: `cmd` + `f` (Windows / Linux: `ctrl` + `f`).

20. Find and replace: `cmd` + `r` (Windows / Linux: `ctrl` + `r`).

21. Move hardcoded strings to resources: `option` + `return` (Windows / Linux: `alt` + `enter`). The shortuct must be used when a caret is on a text. Check the gif below:

    ![alenter](/images/altenter.gif)

    If you use that shortcut globally, the IDE will do *Project quick fix (show intention actions and quick fixes)*.

22. Build and run: `control` + `r` (Windows / Linux: `shift` + `F10`).



## Plugins

1. [Key promoter](https://plugins.jetbrains.com/plugin/4455) - a plugin which will help you to use a keyboard more often :smile:
2. [String Manipulation](https://plugins.jetbrains.com/plugin/2162) - a plugin which provides actions for text manipulation (e.g. toggling styles like camelCase, hyphen-lowercase etc., capitalize text and many more).
3. [Android Material Design Icon Generator](https://github.com/konifar/android-material-design-icon-generator-plugin) - this plugin helps you to set Material Design icons to your Android project. After installation you can use a shortcut: `cmd` + `shift` + `m` to generate an icon (by default).
4. [ButterKnifeZelezny](https://github.com/avast/android-butterknife-zelezny) - simple plugin that allows one-click creation of Butterknife view injections.
5. [IntelliJ/Android Studio Plugin for Android Parcelable boilerplate code generation](https://github.com/mcharmas/android-parcelable-intellij-plugin) - a plugin that generates an Android Parcelable implementation based on fields in the class.
6. [ADB Idea](https://github.com/pbreault/adb-idea) - a plugin that helps and automates adb commands to:
    - Uninstall an application
    - Kill the application
    - Start the application
    - Restart the application
    - Clear the application data
    - Clear the application data and restart
7. [Genymotion plugin](https://www.genymotion.com/plugins/) - this plugin allows you to create and start Genymotion virtual devices from Android Studio.
8. [Android Methods Count](http://www.methodscount.com/plugins) - a plugin that parses your Android library dependencies and shows the methods count as an handy hint.
9. [Git Flow Integration](https://plugins.jetbrains.com/plugin/7315) - a plugin for introducing a Git Flow branching model.[^3]
10. [Builder plugin](https://plugins.jetbrains.com/plugin/7567) - a plugin (from Square) that generates a static nested Builder for a class.

## Resources

1. [Android Studio Tips of the Day by Philippe Breault](https://plus.google.com/collection/wtO0PB)
2. [Keyboard Shortcuts Reference](https://developer.android.com/studio/intro/keyboard-shortcuts.html)
3. [(About) 10 Things You (Probably) Didn’t Know You Could do in Android Studio by Reto Meier](https://medium.com/google-developers/about-10-things-you-probably-didn-t-know-you-could-do-in-android-studio-de231071b375#.toxstt9em)
4. [Mouseless Driven Development by Hadi Hariri](https://vimeo.com/98922030)
5. [Android Studio Like a Boss by Philippe Breault](https://realm.io/news/360andev-philippe-breault-android-studio-ide-like-boss-structural-search-refactoring-java/)
6. [Android Studio for Experts (Android Dev Summit 2015)](https://www.youtube.com/watch?v=Y2GC6P5hPeA)
7. [Android Studio Tips and Tricks by Michael Evans](http://michaelevans.org/blog/2016/01/06/android-studio-tips-and-tricks/)
8. [Meet Android Studio](https://developer.android.com/studio/intro/index.html)
9. [Android Studio – Tips and Tricks by Donn Felker](http://www.donnfelker.com/android-studio-tips-and-tricks-part-1/)
10. [Debug Your App with Android Studio](https://developer.android.com/studio/debug/index.html)
11. [What are some of your must-have plugins for - Reddit discussion](https://www.reddit.com/r/androiddev/comments/3ktqyb/what_are_some_of_your_musthave_plugins_for/)

That’s it! Please let me know about your useful tips & tricks or resources.

---
[^1]: [IntelliJ Idea Viewing Modes](https://www.jetbrains.com/help/idea/2016.2/intellij-idea-viewing-modes.html)
[^2]: [Cutting, Copying and Pasting in IntelliJ IDEA](https://www.jetbrains.com/help/idea/2016.2/cutting-copying-and-pasting.html)
[^3]: [A successful Git branching model](http://nvie.com/posts/a-successful-git-branching-model/)
