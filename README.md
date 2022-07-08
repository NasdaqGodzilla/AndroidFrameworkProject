# AndroidFrameworkProject
Put Android framework source code into Android Studio.

将Android Framework源码导入到Android Studio中。

Both code search, analysis, debugging are all available, not only for reading.

代码搜索、分析、调试功能均可用，不仅用于阅读。

- [x] Code jump
- [x] Code analysis(Data Flow, Search/Find, Call Hierarchy)
- [x] Debugging(Attach debugger to process and debug by step, debug by breakpoint)

Branch of framework source code: android-12.1.0_r11

Commit of framework source code: 7920f82a88b46236928f0ce24154dcbb6c780b74 [Wed Jun 01 20:45:27 2022 +0000]

# Quick setup
1. Star and then clone.
    1. `git clone -b project-android-12.1.0_r11 git@github.com:NasdaqGodzilla/AndroidFrameworkProject.git`
    2. `git checkout project-android-12.1.0_r11`
    3. `git submodule update --init`
    4. Note: All done. The commands as below is used to check if source code is under the right branch.
    5. `cd frameworks/base`
    6. `git checkout android-12.1.0_r11`
    7. `git switch -c android-12.1.0_r11`
2. Open android.ipr by Android Studio.

Framework source code is added in as a git submodule. So command as below can fetch or update it.

使用下面的命令更新作为submodule的framework代码.

```
git submodule update --remote
```

A guide to use android.ipr/android.iml project for Android Studio:

博客记录的Android Studio导入AOSP源码:

[Link](https://nasdaqgodzilla.github.io/2022/06/28/Android-Studio%E5%AF%BC%E5%85%A5AOSP%E7%B3%BB%E7%BB%9F%E6%BA%90%E7%A0%81/)

