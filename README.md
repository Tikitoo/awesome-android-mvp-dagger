# awesome-android-mvp-dagger
最近这几天在学习MVP 模式，也是学的一塌糊涂，所以参考Google 的文章和Github 的项目来学习，所以来汇总一些好的文章和项目。


## 关于
我们都知道MVC 模式，MVP 就是基于MVC 的模式上的一个演化版本。在MVC模式中，Activity应该是属于View这一层。而实质上，它既承担了View，同时也包含一些Controller的东西在里面。随着项目的迭代更新，这对开发很不友好，耦合度也原来越高，项目越来越难维护，而MVP 就是解决这样的痛点。把Activity的View和Controller抽离出来就变成了View和Presenter。


## 文章
- [dependency-injection at master - android-cn/blog](https://github.com/android-cn/blog/tree/master/java/dependency-injection)
- [Android MVP模式 简单易懂的介绍方式 - Kaede's Studio](http://kaedea.com/2015/10/11/android-mvp-pattern/)
- [Dagger on Android－Dagger2详解](http://blog.fidroid.com/post/android/dagger-on-android-dagger2xiang-jie)
- [Android Basic Project Architecture for MVP — mobiwise blog — Medium
](https://medium.com/mobiwise-blog/android-basic-project-architecture-for-mvp-72f4b33252d0)
- [A useful stack on android #1, architecture · Saúl Molinero](http://saulmm.github.io/2015/02/02/A-useful-stack-on-android-1,-architecture/)
- [MVP for Android: how to organize the presentation layer](http://antonioleiva.com/mvp-android/)
- [Dependency injection on Android: Dagger (Part 1)](http://antonioleiva.com/dependency-injection-android-dagger-part-1/)
- [Dependency injection on Android: Dagger (Part 2)](http://antonioleiva.com/dagger-android-part-2/)
- [Dagger: Scoped object graphs (Part 3)](http://antonioleiva.com/dagger-3/)
- [MVP模式在Android开发中的应用 - Vector_Yi的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/vector_yi/article/details/24719873)
- [android-tech-frontier/androidweekly/ 一种在android中实现MVP模式的新思路](https://github.com/bboyfeiyu/android-tech-frontier/tree/master/androidweekly/%E4%B8%80%E7%A7%8D%E5%9C%A8android%E4%B8%AD%E5%AE%9E%E7%8E%B0MVP%E6%A8%A1%E5%BC%8F%E7%9A%84%E6%96%B0%E6%80%9D%E8%B7%AF)
- [Android中的MVP | Rocko's blog](http://rocko.xyz/2015/02/06/Android%E4%B8%AD%E7%9A%84MVP/)
- [Android Basic Project Architecture for MVP — mobiwise blog — Medium](Android MVP — An Alternate Approach)
- [用MVP架构开发Android应用|开源实验室 - 张涛](http://www.kymjs.com/code/2015/11/09/01/)


## 开源框架
- [antoniolg/androidmvp](https://github.com/antoniolg/androidmvp)<br />
MVP Android Example
- [kymjs/TheMVP](https://github.com/kymjs/TheMVP)<br />
An Android MVP Architecture Diagram Framwork.


## 开源项目
- [rallat/EffectiveAndroid](https://github.com/rallat/EffectiveAndroid) <br />
This sample project shows how to apply MVP and Clean architecture on an Android app
- [saulmm/Material-Movies](https://github.com/saulmm/Material-Movies) <br />
An application about movies with material design
- [glomadrian/MvpCleanArchitecture](https://github.com/glomadrian/MvpCleanArchitecture) <br />
A sample project using Clean architecture and MVP in Android
- [grandstaish/hello-mvp-dagger-2](https://github.com/grandstaish/hello-mvp-dagger-2) <br />
Android MVP example code using RxJava, Retrolambda, Dagger 2, and more
- [yydcdut/PhotoNoter](https://github.com/yydcdut/PhotoNoter) <br />
Material Design风格的开源照片笔记。(MVP+Dagger2+RxJava+Dex分包异步加载)
- [antoniolg/DaggerExample](https://github.com/antoniolg/DaggerExample) <br />
Android project using Dagger library
- [bduncavage/recyclerViewToTheRescue](https://github.com/bduncavage/recyclerViewToTheRescue) <br />
Examples of how to use RecyclerView to achieve complex list UIs



