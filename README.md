# ScreenFit

![Release](https://jitpack.io/v/HaowenLee/ScreenFit.svg)

In order to better use the screen fit in multiple items of the individual

Base on 1280x720 screen.

## Thanks

[Android 屏幕适配方案](http://blog.csdn.net/lmj623565791/article/details/45460089)

## Usage

###### Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

###### Step 2. Add the dependency

```
dependencies {
        compile 'com.github.HaowenLee:ScreenFit:1.0'
}

```

```
<View
        android:layout_width="@dimen/x360"
        android:layout_height="@dimen/y360"
        android:background="@android:color/black"/>
```