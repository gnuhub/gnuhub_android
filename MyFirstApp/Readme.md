创建项目
=============
```
 android create project --target 1 --name MyFirstApp \
 --path /Users/stallman/tmp/android/MyFirstApp --activity MainActivity \
 --package com.example.myfirstapp
 ```
编译项目
===========
```
ant debug
```
安装程序
==========
```
android avd (启动一个模拟器 解锁)
adb kill-server
adb start-server
adb install bin/MyFirstApp-debug.apk
```