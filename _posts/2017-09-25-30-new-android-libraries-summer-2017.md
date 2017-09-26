---
layout:     post
title:      30 new Android Libraries and Projects released in Summer 2017 which should catch your attention
date:       2017-09-25
summary:    The summer is over and this is a great time to present my subjective list of 30 Android libraries and projects released in the last 3 months.
categories: libraries android
---

The summer is over and this is a great time to present my subjective list of 30
Android libraries and projects released in the last 3 months. Some of them can
be used in production, some of them definitely not, but playing with all of them
will be pure fun. They are definitely worthy to check. Enjoy!

![](https://cdn-images-1.medium.com/max/2000/1*9hIUb4TpxYkHehxMb7KpEw.jpeg)

1.  [MaterialStepperView](https://github.com/fython/MaterialStepperView)  
    This is a library which implements
    [Steppers](https://material.io/guidelines/components/steppers.html) from
    Material Design Components.

    ![](https://cdn-images-1.medium.com/max/1600/1*bjtY4wWPFU49tRpoec2HHw.png)

    Currently, there is only Vertical Stepper View but more styles will come in the
    future. You can check, how it looks below:

    ![](https://cdn-images-1.medium.com/max/1600/1*JiufJdLtcaftU1xTPkQczg.gif)

    You can customise normal/active point colour, done icon, as well as enable
    animation and set its duration. To check it, please visit [Set item values and
    styles](https://github.com/fython/MaterialStepperView/wiki/Set-item-values-and-styles)
    on its Github. <br> This library supports API 17+ and has a quite comprehensive
    wiki available
    [here](https://github.com/fython/MaterialStepperView/wiki/Vertical-Style).


2. [MultiSnapRecyclerView](https://github.com/TakuSemba/MultiSnapRecyclerView)

    > This is an Android Library for multiple snapping of RecyclerView.
      MultiSnapRecyclerView easily provides a snapping feature to your RecyclerView.

      ![](https://cdn-images-1.medium.com/max/1600/1*B-x5gvQsg-PVazc4kaPvXQ.gif)

    Currently it offers:

    * gravitated snapping to `start,` `end` and `center,`
    * `snap count` to specify a number of items to scroll over,
    * support for horizontal and vertical scrolling,
    * listener to be called when snapped.


3. [Garland View for Android](https://github.com/Ramotion/garland-view-android)

    This is a library that we can consider as a skeleton for creating layouts as
    presented below:

    ![](https://cdn-images-1.medium.com/max/1600/1*TaFbvMple7_wD4PyNKiGZg.gif)

    > `GarlandView` consists of classes for inner items that are scrolled vertically
    and outer items that are scrolled horizontally, and each of which contains one
    inner item.

    Rest of the important information you can find in *README*. There is also an
    example app. The library supports API 19 and above.



4. [VegaLayoutManager](https://github.com/xmuSistone/VegaLayoutManager)

    This is a customised `LayoutManager` — fade and shrink the head itemView when
    scrolling. It was inspired [by this Dribble
    project](https://dribbble.com/shots/3793079-iPhone-8-iOS-11).

    ![](https://cdn-images-1.medium.com/max/1600/1*FCNvg5C5teR3UvUmiscWEw.gif)


5. [ExpandableLayout](https://github.com/iammert/ExpandableLayout)

    The name of this library is self-explanatory. It is a expandable layout, based
    on `LinearLayout`.

    ![](https://cdn-images-1.medium.com/max/1600/1*xlkEisyaCLACSSnN_MXBjQ.png)

    *README* contains all information you need to get started. <br> It is
    well-documented. In addition, there is an example app to quickly jump to the
    code.


6. [SwipeBackLayout](https://github.com/gongwen/SwipeBackLayout)

    > `SwipeBackLayout` is a library that can finish an Activity by using
    gestures.<br> You can set the slide direction, such as FROM_LEFT, FROM_TOP,
    FROM_RIGHT and FROM_BOTTOM.<br> You can also set whether it can only slide from
    the edge.

    ![](https://cdn-images-1.medium.com/max/1200/1*G_WzLxtUZcgrmwi1AlimPQ.gif)

    ![](https://cdn-images-1.medium.com/max/1200/1*j1aa1cmxwiyU5sf24inHAQ.gif)

    `SwipeBackLayout` must contain only one direct child, such as:

    * `LinearLayout`, `RelativeLayout`, `FrameLayout`, `TableLayout` etc.
    * `ScrollView`, `HorizontalScrollView`, `NestedScrollView` etc.
    * `RecyclerView`, a subClass of `AbsListView`(`ListView` etc.)
    * `ViewPager`, `WebView` etc.

    The project has a comprehensive documentation, sample app and an APK.


7. [SmartCropper](https://github.com/pqpo/SmartCropper)

    > This is a library for cropping image in a smart way that can identify the border
    > and correct the cropped image. Applicable to ID cards, business cards, documents
    and other photos of the crop.

    ![](https://cdn-images-1.medium.com/max/1600/1*x7sl--C_dBVQOpd0Vh1NsQ.png)

    ![](https://cdn-images-1.medium.com/max/1600/1*OH8g6acqrhYx_-koGwB0ww.gif)

    Features:

    * Crop image in a smart way that can identify the border,
    * support drag anchors, magnifying glass effect to enhance the positioning
    experience,
    * use the perspective transform to crop and correct the selection to restore the
    front image,
    * support rich UI settings, such as auxiliary lines, mask, anchor, magnifying
    glass and so on.

    Currently, the library uses optimised points sorting algorithm. <br>
    `CropImageView` has selection magnifying effect and it can use `CropImageView`
    `XML` settings.

8. [Date Range Picker](https://github.com/savvisingh/DateRangePicker)

    > Date Range Picker is a Calendar Picker View to show a customised Date Range
    > Picker with improved UI.

    ![](https://cdn-images-1.medium.com/max/1200/1*ECYqRU_ScUiG_Zmgj7pDew.png)

    ![](https://cdn-images-1.medium.com/max/1200/1*hisRWS6xuHzQIghj_crgnQ.png)

    A description of the project is well-written and easy to read.

9. [StoriesProgressView](https://github.com/shts/StoriesProgressView)

    Everybody knows Stories which Facebook and Instagram presented on their apps.
    Here is a library which introduces `StoriesProgressView` which extends
    `LinearLayout` and allows you to add View like below:

    ![](https://cdn-images-1.medium.com/max/1600/1*fj5dEl8-MnuKCx7R7qzL-Q.gif)

    The project contains a short but comprehensive *README* along with sample app.

10. [CosmoCalendar](https://github.com/AppliKeySolutions/CosmoCalendar)

    This library is a custom calendar which offers many features and UI
    modifications like:

    * changing calendar orientation,
    * setting custom text colours,
    * setting selection types and colours,
    * defining navigation buttons etc.,
    * many more.

    ![](https://cdn-images-1.medium.com/max/1600/1*jYTxyU5rWqhlz0hQH4gtrA.png)

    ![](https://cdn-images-1.medium.com/max/1600/1*0X_vg52crmVGvSPdSiF1lw.png)

11. [Reflow Text Animator](https://github.com/shazam/reflow-animator)

    I hope everybody heard about [Plaid app](https://github.com/nickbutcher/plaid).
    This library developed by Shazam Engineering team, is a

    > port of [Plaid’s ReflowText](https://github.com/nickbutcher/plaid/blob/master/app/src/main/java/io/plaidapp/ui/transitions/ReflowText.java)
    that allows easily transitioning between sibling TextViews — no matter their
    size or style.

    The library is really easy to use, plug and play!

    ![](https://cdn-images-1.medium.com/max/1600/1*eoON3oEDIl1fZhrlv0zclg.gif)

12. [AdaptiveIconPlayground](https://github.com/nickbutcher/AdaptiveIconPlayground)

    This is not a library, but a standalone Android app developed by [Nick
    Butcher](https://medium.com/@crafty) for experimenting with [adaptive
    icons](https://developer.android.com/preview/features/adaptive-icons.html).
    According to the *README*:

    > This app finds all installed apps supporting an adaptive icon and displays them
    > in a grid. It then allows you to toggle different mask shapes (approximating how
    the icon might display on different devices) and explore visual effects may be
    applied. Currently offered:<br> Layer translation parallax based on scroll<br>
    Layer scale parallax based on touch

    ![](https://cdn-images-1.medium.com/max/1600/1*GhKpsdfQ-I84WaWyFtTYkA.gif)

13. [Tivi](https://github.com/chrisbanes/tivi)

    ![](https://cdn-images-1.medium.com/max/1600/1*N0HrUsY7PWNhpHvxEZ_88w.png)

    Tivi is an application which tracks TV shows and it is connected to Track.tv. It
    is developed by [Chris Banes](https://medium.com/@chrisbanes). The work is still
    in progress but what is important, it uses the cutting-edge components,
    libraries and tools which includes: [Kotlin](https://kotlinlang.org/),
    [RxJava](https://github.com/ReactiveX/RxJava) 2, usage of all of the
    [Architecture
    Components](https://developer.android.com/topic/libraries/architecture/) (Room,
    LiveData and Lifecycle-components) and usage of
    [dagger-android](https://google.github.io/dagger/android.html) for dependency
    injection.

14. [RxIdler](https://github.com/square/RxIdler)

    This is an `IdlingResource` for Espresso which wraps an RxJava `Scheduler`
    developed by [Square Engineering](https://medium.com/@SquareEng). It supports
    RxJava 1 and RxJava 2 as well. Happy Instrumentation testing!


15. [MRichEditor](https://github.com/Even201314/MRichEditor)

    This is a rich text editor sample (based on
    [summernote](https://github.com/summernote/summernote)). <br> It supports many
    features, including: Bold, Italic, Underline, Strike-through, Headings (1, 2, 3,
    4, 5, 6), Paragraph, Quote, (Un)Ordered List, Code, Horizontal Rule, Link,
    Image, Justify (Center, Fill, Left, Right), Subscript, Superscript, Font Name
    and Size, Indent, Outdent, Undo / Redo.

    ![](https://cdn-images-1.medium.com/max/1600/1*tMe4oaCwVYaY3kSjzuKhEQ.gif)

    ![](https://cdn-images-1.medium.com/max/1600/1*PW4pHasCqLqlq_BhecGuXg.gif)

    In this case you need to base on the sample app, as there is almost no
    documentation.

16. [Android Clean Architecture
Boilerplate](https://github.com/bufferapp/android-clean-architecture-boilerplate)

    This is boilerplate app that shows a clean architecture approach to Android apps
    developed by [Buffer](https://medium.com/@buffer) team and [Joe
    Birch](https://medium.com/@hitherejoe).

    ![](https://cdn-images-1.medium.com/max/1600/1*sPoW9RyB4DSPFSJkDmNp1g.png)

    Reasons for creating this boilerplate:

    > To experiment with modularisation.

    > To share some approaches to clean architecture.

    > To use as a starting point in future projects where clean architecture feels
    > appropriate.

    The project is written 100% in Kotlin with both UI and Unit tests. <br> It is
    really well-documented and great for education purposes! 100% recommendation.

17. [RxJava2Debug](https://github.com/akaita/RxJava2Debug)

    If you use RxJava, you know that sometimes it is difficult to read exceptions
    and find an issue in your Rx stream. And this is the reason why this library was
    created. You can read more about rational in
    [README](https://github.com/akaita/RxJava2Debug).

    The library offers:

    * stack trace generation,
    * stack trace filtering.

18. [Resizer](https://github.com/hkk595/Resizer)

    > Resizer is a lightweight and easy-to-use Android library for image scaling. It
    > allows you to resize an image file to a smaller or bigger one while keeping the
    aspect ratio.

    The library is inspired by [Compressor](https://github.com/zetbaitsu/Compressor)
    library.

    The library specification:

    Minimum SDK: API 21

        Default settings:
        targetLength: 1080
        quality: 80
        outputFormat: JPEG
        outputDirPath: the external files directory of your app

        Supported input formats:
        BMP
        GIF
        JPEG
        PNG
        WEBP

        Supported output formats:
        JPEG
        PNG
        WEBP

        Supported quality range: 0~100
        The higher value, the better image quality but larger file size
        PNG, which is a lossless format, will ignore the quality setting


19. [FaceDetector](https://github.com/Fotoapparat/FaceDetector)

    This library allows you to detect faces in real time on a camera preview. It
    greatly works with [Fotoapparat](https://github.com/Fotoapparat/Fotoapparat)
    library, but is supports also other camera libraries and sources. <br> The usage
    is simple and the project is quite well documented.

    ![](https://cdn-images-1.medium.com/max/1600/1*d4VarbyEF9J8q8sZ4fVA_w.gif)


20. [RxGps](https://github.com/florent37/RxGps)

    This is another library
    from [Florent Champigny](https://medium.com/@florentchampigny). It easily finds
    a current location for us. It is RxJava2 compatible. It also automatically asks
    for GPS runtime permissions and checks if play services are available for you.

21. [MapMe](https://github.com/TradeMe/MapMe)

    > MapMe is an Android library for working with Maps. MapMe brings the adapter
    > pattern to Maps, simplifying the management of markers and annotations.

    ![](https://cdn-images-1.medium.com/max/1600/1*4nbsPR2SjBYMJYTCoVDm0Q.png)

    MapMe works with Google Maps and Mapbox. *README* is comprehensive and the
    library is written in Kotlin.

22. [RevelyGradient](https://github.com/revely-inc/co.revely.gradient)

    This is a library for an easy gradient management.

    ![](https://cdn-images-1.medium.com/max/1600/1*l8g92z15w5dIZOq8Z9FfKw.gif)

    You can use it in Java or in Kotlin. Documentation is short but enough to start
    with ease.

23. [LiteUtilities](https://github.com/gurleensethi/LiteUtilities)

    This is a library written in Kotlin, which helps to eliminate boilerplate from
    your code. Currently it offers:

    * [RecyclerUtils](https://github.com/gurleensethi/LiteUtilities#recyclerutils) —
    Remove the need to make an adapter everytime, set up recycler adapter in as
    little as 4 lines.
    * [ScrollUtils](https://github.com/gurleensethi/LiteUtilities#scrollutils) —
    Easily hide/show FloationActionButton on scroll when using RecyclerView or
    NestedScrollView.
    * [ToastUtils](https://github.com/gurleensethi/LiteUtilities#toastutils) —
    Creating toasts are just a function away.
    * [SPUtils](https://github.com/gurleensethi/LiteUtilities#sputils) — Simple DSL
    for Shared Preferences.
    * [ValidatorUtils](https://github.com/gurleensethi/LiteUtilities#validatorutils) —
    Fast and simple text validation.
    * [LogUtils](https://github.com/gurleensethi/LiteUtilities#logutils) — Simple and
    easy android logging.

24. [KOIN](https://github.com/Ekito/koin)

    > KOIN is a dependency injection framework that uses Kotlin and its functional
    > power to get things done!

    ![](https://cdn-images-1.medium.com/max/1600/1*WnM7ySFug2PSHP5E9tR2Qg.png)

    According to the author, there is:

    * No proxy/CGLib,
    * No code generation,
    * No introspection

    Its documentation is really good, with examples and
    [wiki](https://github.com/Ekito/koin/wiki). There are also contact information
    (even with Slack).

25. [koptional](https://github.com/gojuno/koptional)

    > Minimalistic Optional type for Kotlin that tries to fit its null-safe type
    system as smooth as possible.

    Rationale according to authors:

    > *We don’t think that Kotlin itself needs *`Optional`* because it has strong
    null-safe type system that effectively eliminates need in such a wrapper.
    However there are APIs and libraries like *[RxJava
    2](https://github.com/ReactiveX/RxJava/)* which don't accept *`null`*values.*

    > *We also think that in many cases you can use *`sealed class`*es to express
    absent values, however in simple cases like passing *`String?`* through Rx
    stream *`Optional`* is a more convenient solution.*

    For more go to their [Github](https://github.com/gojuno/koptional).


26. [Parallax](https://github.com/imablanco/Parallax)

    This is an easy parallax `View` for Android simulating Apple TV App Icons.

    ![](https://cdn-images-1.medium.com/max/1600/1*BIV4gW3Ondp70_VE-Rz_iw.gif)

    *README* is really good and worthy to check.

27. [droid-vizu](https://github.com/wotomas/droid-vizu)

    > Droid-vizu aims to provide customised visualisation effects by easily swapping
    Renderer to get cool effects

    ![](https://cdn-images-1.medium.com/max/1600/1*J2TGNekH3ljkOZunfCP4KQ.gif)

28. [Drone](https://github.com/cesarferreira/drone)

    This is not the Android library but a library manager delivered by [César
    Ferreira](https://medium.com/u/e2014d14afbc). It was written due to jealousy of
    the node.js community for their fast and reliable dependency managers. So
    instead of googling a library, checking it, reading docs etc., you just do:

         drone add creator/library module


    For instance:

        drone add jakewharton/butterknife

    ![](https://cdn-images-1.medium.com/max/1600/1*dgBEu-MfcfFTp7qokHqfhA.gif)

    The documentation is really good and this is really worthy to check.

29. [From-design-to-Android-part2](https://github.com/saulmm/From-design-to-Android-part2)

    This is a project covering creating neat UI on Android. This time, [Saúl
    Molinero](https://medium.com/@_SaulMM) covers:

    * using [ShapeShifter](https://github.com/alexjlockwood/ShapeShifter) tool by
    [Alex Lockwood](https://medium.com/@alexjlockwood)
    * `AndroidVectorDrawables`*,*
    * `ScaleDrawables`,
    * Adaptive Icons and more.

    It is a truly great lecture!

    ![](https://cdn-images-1.medium.com/max/1600/1*WfNBTsNo_9ipck02sUoU_w.gif)

30. [Reagent](https://github.com/JakeWharton/Reagent)

    Reagent is a [Jake Wharton](https://medium.com/@jakewharton) place for
    experiments for future reactive libraries. Should you use it? **No.**

*****

That’s it. I hope you enjoyed the list.

*****

If you like my article, please don’t forget to click👏👏👏 to recommend it to others 👏👏👏.
others on [Medium](https://medium.com/@mmbialas/30-new-android-libraries-and-projects-released-in-summer-2017-which-should-catch-your-attention-d3702bd9bdc6).  
Also, to be notified about my new articles and stories, follow me on
[Medium](https://medium.com/@mmbialas) and
[Twitter](https://twitter.com/mmbialas). You can find me on
[LinkedIn](https://www.linkedin.com/in/mmbialas) as well. Cheers!
