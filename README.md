# RxLearning

##[Wiki](https://github.com/ReactiveX/RxJava/wiki)
##[RxJava-Essentials-CN](https://github.com/yuxingxin/RxJava-Essentials-CN)
---
##Example 
- [RengwuxianRxjava](https://github.com/androidmalin/RengwuxianRxjava)-RxJava 之扔物线《给Android开发者的 RxJava 详解》文章中的例子, RxJava 入门教程
- [RxjavaRetrofitDemo](https://github.com/tough1985/RxjavaRetrofitDemo)-A demo show how to use Retrofit with Rxjava
- [RxJavaSamples](https://github.com/THEONE10211024/RxJavaSamples)-收集了RxJava常见的使用场景，例子简洁、经典、易懂
- [Intro-To-RxJava](https://github.com/Froussios/Intro-To-RxJava)-An extensive tutorial on RxJava
- [rxandroidexamples](https://github.com/klnusbaum/rxandroidexamples)-A set of examples for using RxJava in Android
- [RxJavaSamples](https://github.com/rengwuxian/RxJavaSamples)-RxJava 和 Retrofit 结合使用的几个最常见使用方式举例
- [Gifts-for-designers](https://github.com/xcc3641/Gifts-for-designers)-练习Rx
- [RxJava-Android-Samples](https://github.com/kaushikgopal/RxJava-Android-Samples)-A set of examples for using RxJava in Android
- [SeeWeather](https://github.com/xcc3641/SeeWeather)-RxJava+RxBus+Retrofit+Glide+Material Design Weather App

##Much Difficult
- [Meizhi](https://github.com/drakeet/Meizhi)-gank.io unofficial client, RxJava & Retrofit
- [Dota2Helper](https://github.com/uin3566/Dota2Helper)-webview&Retrofit&RxJava&Mvp&GreenDao
- [GankGirl](https://github.com/gaolonglong/GankGirl)-RxJava+Retrofit+Glide
- [GanWuMei](https://github.com/Dimon94/GanWuMei)-Dagger2+Retrofit2+RxJava+Realm
- [RxJoke](https://github.com/JDDJJ/RxJoke)-Rxjava,Retrofit,Dagger2,Mvp
- [RxDownload](https://github.com/ssseasonnn/RxDownload)-The download tool based on RxJava.Support multi-threaded download and breakpoint download

##Another Pack
- [Awesome-RxJava](https://github.com/lzyzsd/Awesome-RxJava)-RxJava resources

##Some Links
- [RxJava](https://github.com/ReactiveX/RxJava)-a library for composing asynchronous and event-based programs using observable sequences for the Java VM.
```compile 'io.reactivex.rxjava2:rxjava:2.0.1'```
- [RxAndroid](https://github.com/ReactiveX/RxAndroid)-RxJava bindings for Android
```compile 'io.reactivex.rxjava2:rxandroid:2.0.1'```
- [RxBinding](https://github.com/JakeWharton/RxBinding)-RxJava binding APIs for Android's UI widgets.
- [RxPermissions](https://github.com/tbruyelle/RxPermissions)-Android runtime permissions powered by RxJava
```compile 'com.tbruyelle.rxpermissions2:rxpermissions:0.9.2@aar'```
- [RxLifecycle](https://github.com/trello/RxLifecycle)-Lifecycle handling APIs for Android apps using RxJava
```
compile 'com.trello.rxlifecycle2:rxlifecycle:2.0.1'

// If you want to bind to Android-specific lifecycles
compile 'com.trello.rxlifecycle2:rxlifecycle-android:2.0.1'

// If you want pre-written Activities and Fragments you can subclass as providers
compile 'com.trello.rxlifecycle2:rxlifecycle-components:2.0.1'

// If you want to use Navi for providers
compile 'com.trello.rxlifecycle2:rxlifecycle-navi:2.0.1'

// If you want to use Kotlin syntax
compile 'com.trello.rxlifecycle2:rxlifecycle-kotlin:2.0.1'
```
- [RxBus](https://github.com/AndroidKnife/RxBus)-Event Bus By RxJava.
```
compile ('com.hwangjr.rxbus:rxbus:2.0.0-beta') {
    exclude group: 'com.jakewharton.timber', module: 'timber'
}
```
- [RxVolley](https://github.com/kymjs/RxVolley)-RxVolley = Volley + RxJava(RxJava2.0) + OkHttp(OkHttp3)
```
compile 'com.kymjs.rxvolley:rxvolley:1.1.4'

// If use okhttp function
compile 'com.kymjs.rxvolley:okhttp:1.1.4'
//or
compile 'com.kymjs.rxvolley:okhttp3:1.1.4'

// If use image-loader function
compile 'com.kymjs.rxvolley:bitmapcore:1.1.4'
```
- [RxCache](https://github.com/VictorAlbertos/RxCache)-Reactive caching library for Android and Java
```compile "com.github.VictorAlbertos.RxCache:runtime:1.8.0-2.x"```
```
dependencies {
    // To use Gson 
    compile 'com.github.VictorAlbertos.Jolyglot:gson:0.0.3'

    // To use Jackson
    compile 'com.github.VictorAlbertos.Jolyglot:jackson:0.0.3'

    // To use Moshi
    compile 'com.github.VictorAlbertos.Jolyglot:moshi:0.0.3'
}
```
- [rx-preferences](https://github.com/f2prateek/rx-preferences)-Reactive SharedPreferences for Android
```compile 'com.f2prateek.rx.preferences2:rx-preferences:2.0.0-RC1'```
- [RxGalleryFinal](https://github.com/FinalTeam/RxGalleryFinal)-Android图片单选/多选、拍照、裁剪、压缩。视频选择和录制。
```
compile 'cn.finalteam.rxgalleryfinal:library:0.0.3'
    //rxgalleryfinal依赖appcompat-v7和recyclerview-v7扩展卡库
    compile 'com.android.support:recyclerview-v7:24.2.0'
    compile 'com.android.support:appcompat-v7:24.2.0'

    //支持以下主流图片加载器，开发者自行选择
    compile 'com.squareup.picasso:picasso:2.5.2'
    compile 'com.facebook.fresco:fresco:0.12.0'
    compile 'com.github.bumptech.glide:glide:3.7.0'
    compile 'com.nostra13.universalimageloader:universal-image-loader:1.9.5'
```
- [RxGroups](https://github.com/airbnb/RxGroups)-Easily group RxJava Observables together and tie them to your Android Activity lifecycle
```compile 'com.airbnb:rxgroups-android:0.3.5'```
- [RxBluetooth](https://github.com/IvBaranov/RxBluetooth)-Android reactive bluetooth
```compile 'com.github.ivbaranov:rxbluetooth:0.1.5'```
- [RxAndroidBle](https://github.com/Polidea/RxAndroidBle)-RxAndroidBle is a powerful painkiller for Android's Bluetooth Low Energy headaches. 
```compile "com.polidea.rxandroidble:rxandroidble:1.1.0"```
- [RxBlur](https://github.com/SmartDengg/RxBlur)-用RxJava处理和操作高斯模糊效果的简单用例。
- [RxCamera](https://github.com/ragnraok/RxCamera)-RxJava style API for android camera
- [RxAndroidAudio](https://github.com/Piasy/RxAndroidAudio)-Maybe the most robust Android Audio encapsulation library, with partial Rx support
- [RxFlux](https://github.com/skimarxall/RxFlux)-RxFlux is a small framework in order to follow Flux design pattern with RxJava functionalities

- [RxJavaApp](https://github.com/jiang111/RxJavaApp)学习的app