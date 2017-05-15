---
layout:     post
title:      30 New Android Libraries released in the Spring of 2017 which deserve your attention
date:       2017-05-15
summary:    This is a list of 30 new Android libraries which have been released since March 2017. They are not in ranked order and, this is my subjective choice.
categories: libraries android
---

This is a list of 30 new Android libraries which have been released since March 2017. They are not in ranked order and,
this is my subjective choice. Obviously, some of them are not production ready but still, you may have lots of fun using them.
Hope you will enjoy it!

![](https://cdn-images-1.medium.com/max/2000/1*3FVOI0HJNamEVvcnmRPqSg.jpeg)

1.  [Matisse](https://github.com/zhihu/Matisse)  
    This is a beautiful local images and videos selector. Main functionalities:

    * Selecting images including JPEG, PNG, GIF and videos including MPEG, MP4,
    * applying custom themes, including two built-in ones,
    * different image loaders,
    * defining custom filter rules,
    * fully operational within  and .

    You can find more in the lib’s [wiki](https://github.com/zhihu/Matisse/wiki).

    ![](https://cdn-images-1.medium.com/max/1600/1*GQApw7XsG6iMWG-ZPSbe1g.png)


2. [Spruce Android Animation
Library](https://github.com/willowtreeapps/spruce-android)

    >  Spruce is a lightweight animation library that helps choreograph the animations
    on the screen. With so many different animation libraries out there, developers
    need to make sure that each view is animating at the appropriate time. Spruce
    can help designers request complex multi-view animations and not have the
    developers cringe at the prototype.

    ![](https://cdn-images-1.medium.com/max/1600/1*Q4T2dAbEqPUF3g4Hj2teSQ.gif)

3. [MaterialChipsInput](https://github.com/pchmn/MaterialChipsInput)  
    Chips were presented in Material Design. They

    > represent complex entities in small blocks, such as a contact. A chip may
    > contain entities such as a photo, text, rules, an icon, or a contact.

    MaterialChipsInput is an implementation of that component for Android. The
    library provides two views :  `ChipsInput` and `ChipView`.

    ![](https://cdn-images-1.medium.com/max/1600/1*j-GtM_dD0w6aSmpwpUsn8g.gif)


4. [Grav](https://github.com/glomadrian/Grav)    
    This library allows to create multiple animations based on points. Take a look —
    how smooth and beautiful animations you can make quite easily. *README* contains
    a lot of examples so you might check it
    [here](https://github.com/glomadrian/Grav).

    ![](https://cdn-images-1.medium.com/max/1600/1*rlnQZT8T78QOBCdi5FwCRQ.gif)

5. [Litho](https://github.com/facebook/litho)  
    Litho is not a library, it is a framework. A really powerful framework to build
    UI in a declarative way. It was developed by Facebook devs, so even if you do
    not want to try it, still it is worthy to observe and follow a development
    process.

    ![](https://cdn-images-1.medium.com/max/1600/1*DGgTaK04UhsTY4gqp05mMA.png)

    Main features include:

    * using a declarative API to define UI components. You simply describe the layout
    for your UI based on a set of immutable inputs and the framework takes care of
    the rest.
    * Asynchronous layout: Litho can measure and layout your UI ahead of time without
    blocking the UI thread.
    * View flattening: Litho uses [Yoga](https://facebook.github.io/yoga/) for layout
    and automatically reduces the number of ViewGroups that your UI contains.
    * Fine-grained recycling: Any component such as a text or image can be recycled
    and reused anywhere in the UI.

6. [Adaptable Bottom
Navigation](https://github.com/bufferapp/AdaptableBottomNavigation)  
    Some time ago Google updated Material Design guideline, and introduced bottom
    navigation bars, as one of several good UI patters to follow in our apps. They
    also added the implementation to the Design Support Library.

    ![](https://cdn-images-1.medium.com/max/1600/1*sha-uKiRhrSOsRDo5RZe5w.png)

    Adaptable Bottom Navigation can easily replace  from Support Library. It is
    implemented in the way how  and  work. This is a short explanation from Buffer
    team:

    > As mentioned, when using the Bottom Navigation View from the Android Support
    > Library, there can be a lot of boilerplate code for the switching of views.
    Because of this, we took inspiration from the TabLayout setupWithViewPager()
    method and created a custom ViewSwapper component that can be attached to a
    Bottom Navigation View to simplify the management of view display.

    You can read more on Github. There is a quite comprehensive documentation and
    explanation why it was implemented (tip: clean architecture 🚀 ).

    ![](https://cdn-images-1.medium.com/max/1600/1*ROB6Jd_XWr1x2CPdTCoF5A.gif)

7. [PatternLockView](https://github.com/aritraroy/PatternLockView)    

    > This library allows you to implement pattern locking mechanism in your app
    > easily and quickly. It is very easy to use and there are plenty of customization
    options available to change the functionality and look-and-feel of this view to
    match your needs.

    > It also supports RxJava 2 view bindings, so if you are a fan of reactive
    > programming (just like me), you can get a stream of updates as the user draws
    the pattern.

    The *README* is full of examples, so it is easy to start with the library.

    ![](https://cdn-images-1.medium.com/max/1600/1*Fog7A-1Hyw77L_sHfEWNYg.gif)


8. [Isometric](https://github.com/FabianTerhorst/Isometric)  
    This is a library which helps to draw isometric shapes. In my opinion, it is one
    of the coolest libraries in that list, as it reminds me of [Monument
    Valley](https://play.google.com/store/apps/details?id=com.ustwo.monumentvalley)
    game.  
    The library supports drawing multiple shapes, paths and complex
    structures, like the example below.

    ![](https://cdn-images-1.medium.com/max/1600/1*I5ppugT8DDwPNTRcq7rrlw.png)

9. [UltraViewPager](https://github.com/alibaba/UltraViewPager)  
    We can treat this library as a  extension that encapsulates many features,
    mainly to provide a unified solution for multi-page switching scenarios.

    ![](https://cdn-images-1.medium.com/max/1600/1*Ara4N3vAGmrAJk7Q9QqWOg.gif)

    UltraViewPager supports:

    * horizontal scrolling and vertical scrolling,
    * multi views in one `ViewPager`
    * switching views circularly. For example, if there are 3 views to display in a `ViewPager`,
    it should switch back to the first view after the third view,
    * auto-scrolling feature (implemented timer using `Handler`),
    * setting max-height and max-width,
    * setting the aspect ratio,
    * indicating the view we are currently (circle and icon),
    * built-in two kinds of page transition animations.

    This library has a good documentation as well.

10. [InfiniteCards](https://github.com/BakerJQ/Android-InfiniteCards)  
    This library helps to implement UI cards and then switch them with a nice
    animation.

    ![](https://cdn-images-1.medium.com/max/1600/1*Dnv5sz98ANxXCB8qJC8RvA.gif)

11. [SlidingRootNav](https://github.com/yarolegovich/SlidingRootNav)  
    This is a library which we can consider as a DrawerLayout-like , where a
    *drawer* is hidden under the content view, and then can be shifted to make the
    drawer visible. *REAMDE* is quite comprehensive and it is worthy to check for
    sure.

    ![](https://cdn-images-1.medium.com/max/1600/1*jJoZS_JY3t1l_AMb39d_Dg.gif)

12. [PasscodeView](https://github.com/hanks-zyh/PasscodeView)  
    It is just a view where you can type your password. But fancy one!

    ![](https://cdn-images-1.medium.com/max/1600/1*unInpDbseFRq4XDwuExgDg.gif)

13. [MusicWave](https://github.com/akshay2211/MusicWave)  
    This library allows to represent sound as a gradient colored visualisation.

    ![](https://cdn-images-1.medium.com/max/1600/1*7REZrDOfphLbOA_f53YX2A.gif)

14. [ShadowImageView](https://github.com/yingLanNull/ShadowImageView)  
    This library helps you to add more meaningful shadow to your images. According
    to *README*, it is

    > More exquisite shadow effect, used in some special scene to enhance the user
    > experience.

    Also, it is easy to use.

    ![](https://cdn-images-1.medium.com/max/1600/1*qIHLw5RISErB-2gH0mYoLA.png)

15. [PolygonDrawingUtil](https://github.com/stkent/PolygonDrawingUtil)  
    This is an efficient Android utility class for drawing regular polygons on a `Canvas`.
    We can specify:

    * Number of sides (≥ 3),
    * center coordinates,
    * outer radius (center to vertex),
    * corner rounding radius,
    * polygon rotation,
    * fill/stroke `Paint`.

    ![](https://cdn-images-1.medium.com/max/1600/1*CfJ9YdWV5jiRf8VVRqWpmQ.gif)

16. [Tiny](https://github.com/Sunzxyong/Tiny)  
    This is a second framework on that list. It is responsible for image compression
    and it is quite powerful. Also, it

    > uses asynchronous thread pool to compress image, and will hand out the result in
    > the main thread when compression is completed.

    Effects of compression:

    ![](https://cdn-images-1.medium.com/max/1600/1*L-0cFTmZF5rxG0h4I6XuDQ.png)

17. [ParticleTextView](https://github.com/Yasic/ParticleTextView)  
    This library provides a custom  widget, which can create text from particles
    using a variety of animation effects and configuration properties.

    ![](https://cdn-images-1.medium.com/max/1600/1*AQYO8HkMgkqnrcLBhtHJzQ.gif)

18. [CropIwa](https://github.com/steelkiwi/cropiwa)  
    This is a highly configurable widget for image cropping. The library has a
    modular architecture, which makes it highly configurable. For the info on how to
    configure refer to the [wiki on Github](https://github.com/steelkiwi/cropiwa).

    ![](https://cdn-images-1.medium.com/max/1600/1*YGjNglrMmlmFm230jVJKxQ.gif)

19. [Project Condom](https://github.com/oasisfeng/condom)  

    > This is a thin library to wrap the naked  in your Android project before passing
    > it to the 3rd-party SDK. **It is designed to prevent the 3rd-party SDK from
    common unwanted behaviors which may harm the user experience of your app.**

    And here is the explanation:

    > Massive launch of processes in other apps (common in 3rd-party push SDKs),
    > causing slow app starting and notable lagging on low to middle-end devices. This
    behavior has **chain reaction** effects among apps with similar SDKs, greatly
    aggravating the overall device performance.

20. [AppMethodOrder](https://github.com/zjw-swun/AppMethodOrder)  
    This library allows you to trace all functions calls order. The project is well
    documented and you can find detailed manuals how to use it. The only constraint
    is that, it is written in Chinese, but you can always click *Translate to
    English* in your browser and enjoy this great project.

    ![](https://cdn-images-1.medium.com/max/1600/1*KZqjj4RJtXMbX_bTLYg57Q.png)

21. [Android DebugKit](https://github.com/hulab/debugkit)  
    This is an interesting library. It allows you to create and use special hovering
    debug tool, to trigger actions defined by you in an application. These actions
    can be obviously triggered in runtime, so it may be used for instance during
    feedback writing or testing a phone screen.  
    The library uses Builder pattern. It is easy to use and in *README*, there is one example of the usage.

    ![](https://cdn-images-1.medium.com/max/1600/1*m7jOl4mVJxLQWiKctVqn1A.gif)

22. [Aesthetic](https://github.com/afollestad/aesthetic)  
    This a fresh library and still in beta, but it does a really cool thing — it
    changes your theme dynamically with Rx support! According to the author, this is

    > A fast and easy to use plug-and-play dynamic theme engine. Powered by Rx, for
    > Android apps.

    The documentation is really good, comprehensive and definitely worthy to check
    out.

    ![](https://cdn-images-1.medium.com/max/1600/1*2ioG7_PPEnyvsxlOYwYXXA.png)

23. [EasyCalendar](https://github.com/shichaohui/EasyCalendar)  
    This is an easy custom calendar widget. Main features include:

    * Custom layout for title,
    * custom layout for date,
    * show or hide divider for date,
    * show or hide overflow date,
    * listen to date’s view be clicked.

    The documentation is comprehensive and the library is easy to use.

    ![](https://cdn-images-1.medium.com/max/1600/1*C2HmS-HSYDSyYAfTnWFFzA.gif)

24. [SimpleRatingBar](https://github.com/ome450901/SimpleRatingBar)  
    This library provides two rating bars:

    * BaseRatingBar — without any animation,
    * ScaleRatingBar — with a progressive and scale animation.

    You can see them in a gif below:

    ![](https://cdn-images-1.medium.com/max/1600/1*Bi5K7bdSBfJooypogQ3uCA.gif)

25. [Magellan](https://github.com/wealthfront/magellan)  
    This library is advertised as the simplest navigation library for Android, but
    you need to check if it is worthy for you to use it. <br> Main features:

    * Navigation is as simple as calling  method,
    * you get full control of the backstack,
    * transitions are automatically handled for you.

    It has comprehensive [wiki](https://github.com/wealthfront/magellan/wiki) with
    all explanations needed.

    ![](https://cdn-images-1.medium.com/max/1600/1*M9kdFW2ffupFFvKn8pBhZw.png)

26. [ViewPagerAnimator](https://github.com/StylingAndroid/ViewPagerAnimator)  

    > *ViewPagerAnimator* is a new lightweight, yet powerful *ViewPager* animation
    > library for Android. it is designed to animate arbitrary values as the user
    navigates between pages within a *ViewPager*, and will precisely follow the
    motion of h[is|er] finger. Although the library itself may be of use to some,
    the main purpose of publishing this library is to demonstrate some wonderful API
    subtleties which really come to the fore when using Java 8 extensions which are
    coming our way soon. Sample projects for both Java 7 and Java 8 are provided.

    It is written by [Mark Allison](https://medium.com/@MarkIAllison) and you can
    get more info on his [Styling Android
    blog](https://blog.stylingandroid.com/viewpageranimator-the-basics/).

    ![](https://cdn-images-1.medium.com/max/1600/1*DgobP2nkoGHimTTR_BbcIA.gif)

27. [BlockCanaryEx](https://github.com/seiginonakama/BlockCanaryEx)  
    This is a library, which facilitates finding heavy methods in your code when
    your app blocked. It is based on
    [BlockCanary](https://github.com/markzhai/AndroidPerformanceMonitor).

    ![](https://cdn-images-1.medium.com/max/1600/1*qzxcEHXtIOqrSI2CW69cnw.png)

28. [PaletteImageView](https://github.com/DingMouRen/PaletteImageView)  
    This is quite cool library. It adds a shadows to your images, but the color of
    shadow is in a dominant image color.

    ![](https://cdn-images-1.medium.com/max/1600/1*dOit-xwG0OuwuVcEwQIBZA.gif)

    Documentation is quite poor but I think the code is self-explanatory.

29. [RecyclerRefreshLayout](https://github.com/dinuscxj/ShootRefreshView)  
    This is a refresh animation that opens a camera shutter. In my opinion it is
    really worthy to check, especially in *README* there is a mathematical analysis,
    how to achieve this effect!

    ![](https://cdn-images-1.medium.com/max/1600/1*Wt1Y35Twr0WlD_oRepzNYA.gif)

30. [SlimAdapter](https://github.com/MEiDIK/SlimAdapter)  
    This is an approach to write an Adapter without . Key features include:

    * No `ViewHolders`,
    * no reflection,
    * fluent & simple API,
    * multi-typeable adapter,
    * Kotlin support,
    * Simple `DiffUtil` support.

    ![](https://cdn-images-1.medium.com/max/1600/1*ptkVWOCGRj0wBaO0kNpnEQ.png)

*****

That’s it. I hope you enjoyed the article! If I didn’t mention any other great libraries
released in this Spring, please let me know in the comments below. Let’s keep that list bigger together!

*****

If you like my article, please don’t forget to click ❤ to recommend it to
others on [Medium](https://medium.com/@mmbialas/30-new-android-libraries-released-in-the-spring-of-2017-which-deserve-your-attention-faea359a1915).  
Also, to be notified about my new articles and stories, follow me on
[Medium](https://medium.com/@mmbialas) and
[Twitter](https://twitter.com/mmbialas). You can find me on
[LinkedIn](https://www.linkedin.com/in/mmbialas) as well. Cheers!
