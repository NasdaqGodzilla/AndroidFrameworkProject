# AndroidFrameworkProject
Put Android framework source code into Android Studio.

将Android Framework源码导入到Android Studio中。

Both code search, analysis, debugging are all available, not only for reading.

代码搜索、分析、调试功能均可用，不仅用于阅读。

- [x] Code jump
- [x] Code analysis(Data Flow, Search/Find, Call Hierarchy)
- [x] Debugging(Attach debugger to process and debug by step, debug by breakpoint)

Branch of framework source code: android-11.0.0_r48

Commit of framework source code: 1d9b9ab57d844b18b3b1b4297725141e7788109b [2021-08-16 04:15:29 +0000]

# Quick setup
1. Star and then clone.
    1. `git clone -b project-android-11.0.0_r48 git@github.com:NasdaqGodzilla/AndroidFrameworkProject.git`
    2. `git checkout project-android-11.0.0_r48`
    3. `git submodule update --init`
    4. `cd frameworks/base`
    5. `git checkout -b android-11.0.0_r48`
2. Open android.ipr by Android Studio.

Framework source code is added in as a git submodule. So command as below can fetch or update it.

使用下面的命令更新作为submodule的framework代码.

```
git submodule update --remote
```

A guide to use android.ipr/android.iml project for Android Studio:

博客记录的Android Studio导入AOSP源码:

[Link](https://nasdaqgodzilla.github.io/2022/06/28/Android-Studio%E5%AF%BC%E5%85%A5AOSP%E7%B3%BB%E7%BB%9F%E6%BA%90%E7%A0%81/)

