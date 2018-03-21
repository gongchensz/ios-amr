========

说明
------------

直接兼容Android的amr文件, 实现双方互通
需要与Android互通，可以看一下`AudioRecord.java`，已测试双方互通。


环境需求
------------

Xcode 4.6 或以上

安装
------------

1. git clone 整个工程  

2. 直接打开demo工程跑通

3. 将arm文件拖入你的工程编译

Demo中两个方法的实现可以直接用

```startRecord``` ```stopRecord```



版本更新历史
-------------

1.1

* 兼容armv7和armv7s, 去除armv6支持

1.2

* 增加i386 arm64支持

最后测试
-------------

XCode 9.2 真机 ios10.2
