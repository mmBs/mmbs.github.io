---
layout:     post
title:      30 summertime Android libraries and tools which you don’t want to miss in 2018
date:       2018-09-18
summary:    This is my newest unranked list of Android libraries, tools and projects which you may find interesting or helpful during your day-to-day work.
categories: libraries android
---


# 30 summertime Android libraries and tools which you don’t want to miss in 2018

Summertime is ending (at least in the Northern Hemisphere) and during this time
many great Android libraries and tools were developed and updated.    
This is my newest unranked list of Android libraries, tools and projects which you may
find interesting or helpful during your day-to-day work. They are also great for
an inspiration or experiments.    
I hope you will enjoy it. Let’s start!

![](https://cdn-images-1.medium.com/max/2000/1*gL3e2m_Zt371lSVZpfacBQ.png)
Childish Gambino — Feels Like Summer

***

### 1. [LayoutManagerGroup](https://github.com/DingMouRen/LayoutManagerGroup)

This is a library which offers set of LayoutManagers for RecyclerViews to
achieve features and effects like in the gif below.

![](https://cdn-images-1.medium.com/max/1600/1*4Gsuy-Ad2uDwTdlRNUGwTQ.gif)

These LayoutManagers mainly extend `RecyclerView.LayoutManager` or just
`LinearLayoutManager` and add more functionality on the top of that.

This library has a really short and limited documentation, but, as always, code
is the answer. The best way to get know it, is to go to the [sample
app](https://github.com/DingMouRen/LayoutManagerGroup/tree/master/app) and
check, how it is implemented in `Activities` and `Fragments`.

It is released under Apache 2.0 license and it is really worthy to check.

### 2. [Creative View Pager](https://github.com/tommybuonomo/creative-viewpager)

Creative View Pager is a fresh approach to the `ViewPager` that combines a
header list, which is scrolled smoothly and automatically in a coordination with
the page contents.

![](https://cdn-images-1.medium.com/max/1600/1*tAUmNVYxyOvuJUsL_8RK4A.gif)

The documentation is comprehensive and explains how to use the library.    
It is released under Apache 2.0 license and written almost in 100% in Kotlin.

### 3. [Instabug](https://instabug.com/)

Instabug is

> an in-app feedback and bug reporting tool for mobile apps. With just a simple
> shake, your users or beta testers can [report
bugs](https://instabug.com/bug-reporting) or send in-app feedback and the SDK
will capture an environment snapshot of your user’s device including all console
logs, [server-side network requests](https://instabug.com/network-logging) and
bug reproduction steps compiling all these details in one organised dashboard to
help you debug and fix bugs faster.

![](https://cdn-images-1.medium.com/max/1600/1*KA-XMsvfeGUpnaLyOzy7Ag.gif)

It was recently updated and lots of bug fixes were introduced. In [this blog
post](https://instabug.com/blog/introducing-auto-screen-recording-network-performance-monitoring-crash-severity/)you
can find more about changes. Instabug gives a possibility to:

* report [bugs](https://docs.instabug.com/docs/android-bug-reporting) and
[crashes](https://docs.instabug.com/docs/android-crash-reporting),
* create [in-app surveys](https://docs.instabug.com/docs/android-in-app-surveys)
which is great and really facilitate discussions on the product,
* [request features](https://docs.instabug.com/docs/android-feature-requests)
which we would love to have in the app,
* monitor network performance,
* [auto record a
screen](https://docs.instabug.com/docs/android-auto-screen-recording).

I have been using it since 2016 when I did a research for my product team about
tools which can support their work and our users. I highly recommend this tool.

### 4. [CheckableChipView](https://github.com/okdroid/checkable-chip-view)

This is a checkable widget for Android based on the [EventFilterView from the
Google I/O 2018
app](https://github.com/google/iosched/blob/2696fc7e06826ba2db72de243f0d63f83f4a29b5/mobile/src/main/java/com/google/samples/apps/iosched/ui/schedule/filters/EventFilterView.kt).
It requires Android `minSdkVersion` 21 to work.

![](https://cdn-images-1.medium.com/max/1600/1*CCF5Jq6mW-iK7ikdkjCCqQ.gif)

*README* is comprehensive and allows a quick start with the widget. The initial
implementation was made by [Nick Butcher](https://medium.com/@crafty) and [Jose
Alcérreca](https://medium.com/@JoseAlcerreca) from Google.    
The widget is released under Apache 2.0 license and written in Kotlin.

### 5. [CrunchyCalendar](https://github.com/CleverPumpkin/CrunchyCalendar)

This is light, powerful and easy to use Calendar Widget.

![](https://cdn-images-1.medium.com/max/1600/1*SpjCCHWK88ma0x9EYq7AVQ.png)

It offers a number out of the box features:

* Infinite vertical scrolling in both directions,
* setting date boundaries to restrict scrolling inside of a specific time period,
* single / multiple / range dates selection,
* pre-selecting dates,
* color customization,
* displaying color indicators,
* setting own custom `ItemDecoration`,
* presented as a `View` subclass which can be displayed everywhere: in `Activity`,
`Fragment` or `Dialog`, or can be integrated into another custom `View`.

The documentation is exceptional, with many examples. There is also a sample app
available on
[Github](https://github.com/CleverPumpkin/CrunchyCalendar/blob/master/sample/)
and [Google Play](https://play.google.com/store/apps/details?id=ru.cleverpumpkin.calendar.sample).

This project is released under MIT license.

### 6. [InboxRecyclerView](https://github.com/saket/InboxRecyclerView)

This is a library for building expandable descendant navigation, inspired by
[Google Inbox](http://androidniceties.tumblr.com/post/100872004063/inbox-by-gmail-google-play-link)
and [Reply](https://material.io/design/material-studies/reply.html).

![](https://cdn-images-1.medium.com/max/1600/1*W9O2EdGs3Eg29jefLDHAhw.gif)

> `InboxRecyclerView` can be dropped in existing projects without requiring any
> effort. You can take a look at the [sample
app](https://github.com/saket/InboxRecyclerView/tree/master/sample) for best
practices or [download its
APK](https://github.com/saket/InboxRecyclerView/releases) for trying it out on
your phone.

The author also wrote a [really good
article](https://saket.me/inboxrecyclerview/) about it.     
This library is definitely worthy to check. It is released under Apache 2.0 license.

### 7. [SlideBack](https://github.com/ChenTianSaber/SlideBack)

This is a small but interesting library which provides a `SlideBackView` inside
your `Activity`. To understand what it does, please check the gif below.

![](https://cdn-images-1.medium.com/max/1600/1*UH1iX7YAFNHtaYRT-2-ACQ.gif)

Unfortunately, the documentation is quite poor and written in Chinese.    
I would treat it more like an experiment than a fully operational solution. Still,
you can check the code of a sample app and the library itself.    
It is released under MIT license.

### 8. [DrawableToolbox](https://github.com/duanhong169/DrawableToolbox)

This library creates drawables programmatically and gets rid of the boring and
always repeated `drawable.xml` files.

![](https://cdn-images-1.medium.com/max/1600/1*DeBe3bZJcohc-43Nk0c0Tw.gif)

It is released under Apache 2.0 license. It has a really comprehensive
documentation and works with API 14 and above.

### 9. [ColorPicker](https://github.com/duanhong169/ColorPicker)

This is a library written by the same developer, who wrote DrawableToolbox. It
is just another approach to the colour picker.

![](https://cdn-images-1.medium.com/max/1600/1*GBf-eWYR9cdAebetE9L47Q.gif)

This library has quite good documentation. It is released under Apache 2.0
license and works with API 14 and above. If you need the colour picker in your
app, you can always test and check this one.

### 10. [MvRx](https://github.com/airbnb/MvRx)

This is just huge. MvRx (pronounced mavericks) is the Android framework from
Airbnb that they use for nearly all product development.

> MvRx provides a framework that makes Android screens, from the simplest to the
> most complex, easier to write than before. However, it is built on top of
existing components such as Fragments and architecture components so it doesn’t
constrain you and is easy to incrementally adopt.

The main goal was to build and deliver products faster and with less effort.
MvRx uses the following existing technologies and concepts:

* Kotlin
* Android Architecture Components
* RxJava
* React (conceptually)
* [Epoxy](https://github.com/airbnb/epoxy) (optional but recommended)

Currently, the framework has the version 0.5.0 and it is released under Apache
2.0 license.    
The [documentation](https://github.com/airbnb/MvRx) and
[wiki](https://github.com/airbnb/MvRx/wiki) are also great. Wiki contains
`tl;dr` version, as well as a normal one, with all the explanation needed to
understand the concept.

### 11. [RxRedux](https://github.com/freeletics/RxRedux)

If you heard about [Redux](https://redux.js.org/introduction/motivation), its’
main [concepts](https://redux.js.org/introduction/coreconcepts) and [three
principles](https://redux.js.org/introduction/threeprinciples), you will
probably know what is this library about.     
RxRedux is an implementation based on RxJava (inspired by
[redux-observable](https://redux-observable.js.org/)) that helps to isolate side
effects (A Side Effect is a function of type `(Observable<Action>,
StateAccessor<State>) -> Observable<Action>`).

![](https://cdn-images-1.medium.com/max/1600/1*Zs2fQ9RqGiGPbxD-hc_ddg.png)

> RxRedux is (kind of) a replacement for RxJava’s `.scan()`[
> operator](http://reactivex.io/documentation/operators/scan.html).

*README* is really well-written and also enriched by [this article](https://freeletics.engineering/2018/08/16/rxredux.html).   
This library has version 1.0.0 and it is released under Apache 2.0 license.

### 12. [Emoji Slider](https://github.com/bernaferrari/EmojiSlider)

It is a custom `SeekBar` inspired by [Instagram’s Emoji
Slider](https://instagram-press.com/blog/2018/05/10/introducing-the-emoji-slider/).

![](https://cdn-images-1.medium.com/max/1600/1*ktJvgrwRAt4TT83Wq2caPQ.gif)

The project contains a really good documentation as well as a sample app with
generated `apk`. It has 0.3.0 version and is released under Apache 2.0 license.

### 13. [Covert](https://github.com/TradeMe/Covert)

This is a library which helps to implement [Material Swipe
Actions](https://material.io/design/interaction/gestures.html#types-of-gestures)
in a `RecyclerView`. It is written according to Material Design principles.

![](https://cdn-images-1.medium.com/max/1600/1*9oTAik7-S5cKES2bIcHdMQ.gif)

It is easy to setup thanks to the good documentation. The project is released
under MIT documentation and it has version 1.0.0.

### 14. [PixelShot](https://github.com/Muddz/PixelShot)

This is a library that can save any `View` or `SurfaceView` as an image in the
formats: `JPG/PNG/nomedia`. The library works on a asynchronous task behind the
scenes, handles errors of I/O operations and manages memory allocation for
you.    
You can easily use it to take screenshots inside your app (e.g. for
reporting a bug or an improvement).    
It is quite easy to use and docs are enough just to start. It is released under Apache 2.0 license and supports API
19 and above.

### 15. [WiseFy](https://github.com/isuPatches/WiseFy)

WiseFy is a wrapper for `WifiManager` and `ConnectivityManager` for Android. It
adds easy WiFi configuration and utils on the top of the managers, like:

* adding and removing networks,
* checking device connectivity,
* checking the current network,
* enabling and disabling WiFi and many more.

![](https://cdn-images-1.medium.com/max/1600/1*ew9UQtEFVECWFnP1kzZOpQ.png)

This is not a new library, but some time ago it had huge refactor and it was
rewritten 100% in Kotlin.

The [documentation](https://github.com/isuPatches/WiseFy/tree/3.x/documentation)
is really detailed and definitely worthy to check. License: Apache 2.0.

### 16. [MVICore](https://github.com/badoo/MVICore)

MVICore is a modern MVI framework from [Badoo Tech](https://medium.com/@BadooTech) featuring:

* 100% Kotlin: An easy way to implement your business features in a reactive way
with unidirectional dataflow,
* Scaling with complexity: operate with a single Reducer if needed, with the
option of having the full power of additional components to handle more complex
cases,
* Event handling: A solution to handling events that you don’t want to store in
the state,
* Reactive component binding: A super simple API to bind your reactive endpoints
to each other with automatic lifecycle handling,
* Custom Middlewares: for every single component in the system, with flexible
configuration options,
* Logger: An out-of-the-box logger Middleware,
* Time Travel Debugger: for ALL of your reactive components (not just your state
machine!) with UI controls for recording and playback.

Currently it has version 1.0.0 and really comprehensive
[docs](https://github.com/badoo/MVICore/blob/master/documentation/README.md). If
you want to rewrite your app in MVI way, I think this solution is really worthy
to check.

### 17. [DialerLoading](https://github.com/SaeedMasoumi/DialerLoading)

This library might be useful when developing a custom views. It is a rotary
dialer loading view and can be used as a replacement of e.g. indeterminate
Progress Bar.

![](https://cdn-images-1.medium.com/max/1600/1*5VdnD7L8noeXRj8Fi72mEw.gif)

There is a short *README* in the project, which was released under Apache 2.0
license. Written 100% in Kotlin.

### 18. [HtmlRecycler](https://github.com/m7mdra/HtmlRecycler)

This is an interesting library which converts a simple HTML page into
a`RecyclerView` of native Android widgets powered by [Jsoup library](https://jsoup.org/) and inspired by [Medium Textview](https://github.com/angebagui/medium-textview/).

![](https://cdn-images-1.medium.com/max/1600/1*Bzn3iJD2Egq0NYGVHWwcrw.gif)

This library is under development so treat it more like an experiment than ready
to production code.    
The documentation is good and explains how to use the
lib. It is released under Apache 2.0 license.

### 19. [Android Clean Architecture Components Boilerplate](https://github.com/bufferapp/clean-architecture-koin-boilerplate)

I mentioned about this boilerplate many times but it is really good to follow
[Buffer](https://medium.com/@buffer) tech team efforts. Currently they showcase
how to use [Koin](https://github.com/InsertKoinIO/koin) instead of Dagger as
dependency injection framework.

![](https://cdn-images-1.medium.com/max/1600/1*F73RDaKGEOJQvyvR6WVMAA.png)

The boilerplate is released under MIT license.

### 20. [Splitties](https://github.com/LouisCAD/Splitties)

Splitties is a collection of small independent Android libraries that aims to
make developing apps and libraries for Android (including Wear, TV, Things, Auto
and ChromeOS targeted) easier and more fun.     
I really like the idea of it and it is really worthy to check. According to the author:

> This project is named “Splitties” because it is split in small modules,
> distributed as independent Android libraries, so you can add only the ones you
need to your project/module, helping reduce the size of the final apk.

> Each module has been designed to have a small footprint and be as efficient as
> possible.

The documentation is really comprehensive and the project is released under
Apache 2.0 license.

### 21. [AndroidWM](https://github.com/huangyz0918/AndroidWM)

This is a lightweight android image watermark library that supports encrypted
and invisible digital watermarks.

![](https://cdn-images-1.medium.com/max/1600/1*fYYk-q8azlKSnniUr2urnw.png)

The library is quite powerful and offers building multiple watermarks, selecting
a drawing mode and how we can load resources (from text, `View` or Android
resources). The documentation is really good , there is also a sample app.    
Currently, the library has version 0.1.9 and is released under Apache 2.0
license.

### 22. [Android components](https://github.com/mozilla-mobile/android-components)

This is second collection of libraries in this article. This time it comes from
[Mozilla](https://medium.com/@mozilla) team and it may be useful during building
browsers or browser-like applications.    
The diagram below shows some of available components.

![](https://cdn-images-1.medium.com/max/1600/1*GycIyNJDKasRNCiyKsExOA.png)

The project contains [4 sample apps](https://github.com/mozilla-mobile/android-components/tree/master/samples)
which showcase, how to use various components. It has also a really good
documentation and it is released under MPL 2.0 license.

### 23. [RxBiometric](https://github.com/pwittchen/RxBiometric)

This library adds RxJava and RxKotlin bindings for Biometric Prompt (Fingerprint
Scanner) on Android (added in Android 9 Pie, API Level 28+).

![](https://cdn-images-1.medium.com/max/1600/1*X_ggbGnxGhOUpy3hTBmgYg.png)

According to the [Google Android Developers Blog](https://android-developers.googleblog.com/2018/08/introducing-android-9-pie.html),
when

> your app is drawing its own fingerprint auth dialogs, you should switch to using
> the BiometricPrompt API as soon as possible.

RxBiometric helps you to do that via RxJava stream. It has robust documentation
with usage and examples.    
It is released under Apache 2.0 license.

### 24.
[EnhancedNavigationView](https://github.com/florent37/EnhancedNavigationView)

This is a library which extends Google’s `BottomNavigationView` and add more
interesting look to it.

![](https://cdn-images-1.medium.com/max/1600/1*3u-83coEpNGZA6DwxdBlug.gif)

The project is written in Kotlin, released under Apache 2.0 license and contains
a sample app to test it out.

### 25. [livedata-ktx](https://github.com/Shopify/livedata-ktx)

This is Kotlin extension for `LiveData`, chaining like RxJava delivered by
[Shopify](https://medium.com/@Shopify) team. If you use `LiveData` from Android
Architecture Components, you can replace it with `LiveData KTX` and create
chains like below:

![](https://cdn-images-1.medium.com/max/1600/1*PJa3jweujBJUzduJDWfN6Q.png)

The project is maintained by 4 developers and released under MIT license.

### 26. [Tumbleweed](https://github.com/noties/Tumbleweed)

Tumbleweed is a fork of
[Universal-Tween-Engine](https://github.com/AurelienRibon/universal-tween-engine)
and it

> allows you to create smooth interpolations on every attribute from every object
> in your projects.

![](https://cdn-images-1.medium.com/max/1600/1*RUhtoBZYsgoP42DIAIMi1Q.gif)

Tumbleweed comes with few changes and differences:

* decreased mutation of Tweens and Timelines (split definition and execution of
tweens)
* encapsulated interpolation by introducing specific type (`TweenType<T>`)
* removed pooling (a constant source of unexpected behaviour) and many more.

It has comprehensive docs and is released under Apache 2.0 license. It has also
[sample app](https://github.com/noties/Tumbleweed/blob/master/android-sample)
included to the project.

### 27. [Stylist](https://github.com/uber/stylist)

Stylist is a project delivered by [Uber
Developers](https://medium.com/@UberDevelopers). It is a Gradle plugin written
in Kotlin that generates a base set of Android XML themes. Stylist-generated
themes are created using a stencil and trait system. For instance, if you want
to define text size in Dark and Light themes, you will create following class:

![](https://cdn-images-1.medium.com/max/1600/1*D7j74JjDpmoU9oI7Ltah5Q.png)

And you will get generated XML themes like below:

![](https://cdn-images-1.medium.com/max/1600/1*yJQxNUPLf7NkwaquYbVg4w.png)

Currently, the project has version 0.0.1 and it is released under Apache 2.0
license.

### 28. [RxkPrefs](https://github.com/afollestad/rxkprefs)

This is a small library which provides reactive shared preferences interaction
with very little code. It is designed specifically to be used with Kotlin.    
With a `RxkPrefs` instance, you can retrieve preferences. But it will not be the
raw value of the preference, but an instance of the `Pref` interface which
provides more functionality.     
The library has version 1.0.2 and it is released under Apache 2.0 license.

### 29. [Philology](https://github.com/JcMinarro/Philology)

This library offers an easy way to dynamically replace `Strings` of your Android
App or provide new languages Over-The-Air without needed to publish a new
release on Google Play. How does it work?

> *Philology* doesn’t replace the way you are using resources in your current
> Android Development. Instead, it improves the process by intercepting the value
returned from your hardcoded translation files inside of the app and check if
there is a newer value in the server. This allows for typo fixing, better
wording or even for adding a new language. All in real time, without releasing a
new version of the App.

> With *Philology* you could replace hardcoded texts instantly and win time before
> the new release is done.

It is a really nice idea released under Apache 2.0 license. The project contains
a sample app as well as as really comprehensive documentation.

### 30. [Scarlet](https://github.com/Tinder/Scarlet)

This is a Retrofit inspired `WebSocket` client for Kotlin, Java, and Android
from Tinder dev team. The documentation of this client is really comprehensive
and also covered by [Taming WebSocket with Scarlet](https://tech.gotinder.com/taming-websocket-with-scarlet/) article.    
You can also check it usage by checking realtime Bitcoin price from [Gdax WebSocket Feed](https://docs.gdax.com/#websocket-feed) which is posted as a
[demo app](https://github.com/Tinder/Scarlet/blob/master/demo/src/main/java/com/tinder/app).

Scarlet is driven by a [StateMachine](https://github.com/Tinder/StateMachine)
also presented by Tinder team.

![](https://cdn-images-1.medium.com/max/1600/0*AeXNC3Wk6Sld5m54)

The project is released under BSD 3-Clause license and it has 0.1.4 version.

*****

That’s it! I hope you enjoyed the list and some of the projects inspired you. If
you know any other great library, which was released in past 5 months* and I
didn’t mention about it, please let me know in the comments. You can also check
my other articles that have been released earlier this year or last year:

* [25 new Android libraries, projects and tools worthy to check in Spring
2018](https://medium.com/@mmbialas/25-new-android-libraries-projects-and-tools-worthy-to-check-in-spring-2018-68e3c5e93568)
* [25 new Android libraries and projects to check at the beginning of
2018](https://proandroiddev.com/25-new-android-libraries-and-projects-to-check-at-the-beginning-of-2018-ba3b422bbbb4)
* [30 new Android Libraries and Projects released in Summer 2017 which should
catch your
attention](https://medium.com/@mmbialas/30-new-android-libraries-and-projects-released-in-summer-2017-which-should-catch-your-attention-d3702bd9bdc6)

*****

To be notified about my new articles and stories, follow me on
[Medium](https://medium.com/@mmbialas) and
[Twitter](https://twitter.com/mmbialas). You can find me on
[LinkedIn](https://www.linkedin.com/in/mmbialas) as well. Cheers!
