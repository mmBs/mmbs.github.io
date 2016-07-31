---
layout:     post
title:      CircleCI for Android projects
date:       2016-07-31
summary:    A quick tutorial how to easily set an Android project for CircleCi Continuous Integration
categories: tools ci
---

Today I would like to focus on setting up Android projects for CircleCI Continuous Integration.

CircleCI is a tool which allows you  

>  automatically build and test your changes to make sure you didn’t break anything. [^1]

What really matters to me is a fact that you can use it for **free** (according to a pricing plan, a free version allows you to have infinite amount of repos and users, gives you 1500 build minutes per month, 1 container and 1 concurrent build) and it offers a really **great integration with Github**. I think it is enough just to give it a try.

## Manual

1. Set up your account on [CircleCI website](https://circleci.com/).
2. Go to [Add Projects](https://circleci.com/add-projects) section.
3. Choose your Github account and the choose a repo.
4. You will see a list of available projects and a **Build project** button on the right side of the list.
5. You can click on it to check a process of building the app, but unfortunately the project of your choice won't build.
6. Why? Because You need to add **circle.yml** config file to your project (put it to the git's repo root folder of your project).
7. Right now you should be able to build your project. Please remember that you need adapt the file to your needs (Build Tools version, SDK version etc.). Go through the explanation posted below. After that you should understand what happens in the file and you will be good to set up your own CI for Android projects. Good luck :+1:

## circle.yml explanation for Android developers

My current circle.yml file looks like this below:

{% gist mmBs/a8d8da398f0e780b01556a79e78530d8 %}

The circle.yml file is a simple `YAML` file where you can spell out any tweaks required for your app. This is a general file structure and content:

* *general*: setting up general configuration, for instance where artifacts of the application will be stored
* *machine*: adjusting the VM to your preferences and requirements
* *checkout*: checking out and cloning your git repo
* *dependencies*: setting up your project’s language-specific dependencies
* *database*: preparing the databases for your tests
* *test*: running your tests
* *deployment*: deploying your code to your web servers

As you can see, in the `machine` section you will define your artifacts. You need to change
`YourApplicationName` for your Android project name. In that particular place CircleCI will
generate for you apks of the app.  
In `dependencies` section you will add all project dependencies, as `Build Tools`, `Android SDK`,
`Google Play services` and many more. You can use my gist as a reference and adapt it for your needs.

## Tips

1. Java 8   
By default CircleCI uses Java JDK 7 to build projects. To use Java 8 you need to add `javaJDK`
field in your `machine` section and set it up for Java 8. If you use Gradle dependencies or 3rd
party libraries which use JDK 1.8. you also need to add it.  

2. Retrolambda      
If you want to use [Retrolambda](https://github.com/evant/gradle-retrolambda) in your project, you should add these lines to your `build.gradle`:   
```
retrolambda {
    jvmArgs '-noverify'
}
```

3. Always read all logs which CircleCI returns to you - it is very comprehensive and it allows
you to resolve your issues quickly and effectively.

4. Tests   
You can test your application on an emulator which is preinstalled on the CI machine. Below you can find
a sample of circle.yml for test:

```
test:
  override:
    # start the emulator
    - emulator -avd circleci-android22 -no-audio -no-window:
        background: true
        parallel: true
    # wait for it to have booted
    - circle-android wait-for-boot
    # run tests  against the emulator.
    - ./gradlew connectedAndroidTest
    # copy the build outputs to artifacts
    - cp -r my-project/build/outputs $CIRCLE_ARTIFACTS
    # copy the test results to the test results directory.
    - cp -r my-project/build/outputs/androidTest-results/* $CIRCLE_TEST_REPORTS

```

you can find more about testing Android applications in the [CircleCI official documentation](https://circleci.com/docs/android/).

I hope you found this short post useful! Let me know your thoughts.




## Useful links

1. [https://circleci.com/docs/android/](https://circleci.com/docs/android/)
2. [https://circleci.com/mobile/android/](https://circleci.com/mobile/android/)
3. [http://surajms.com/2016/01/setting-up-android-build-on-circleci/](http://surajms.com/2016/01/setting-up-android-build-on-circleci/)
4. [CircleCI tutorial from Donn Felker](https://www.youtube.com/watch?v=oIRbUGJKcrs)


---
[^1]: Quote from the official CircleCI site.
