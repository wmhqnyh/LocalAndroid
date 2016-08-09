1.[Android-PullToRefresh](https://github.com/chrisbanes/Android-PullToRefresh)

Ps：This project aims to provide a reusable Pull to Refresh widget for Android. It was originally based on Johan Nilsson's library (mainly for graphics, strings and animations), but these have been replaced since.

Image：

![图片](https://raw.githubusercontent.com/chrisbanes/Android-PullToRefresh/master/header_graphic.png)

## Features

 * Supports both Pulling Down from the top, and Pulling Up from the bottom (or even both).
 * Animated Scrolling for all devices.
 * Over Scroll supports for devices on Android v2.3+.
 * Currently works with:
 	* **ListView**
 	* **ExpandableListView**
 	* **GridView**
 	* **WebView**
 	* **ScrollView**
 	* **HorizontalScrollView**
 	* **ViewPager**
 * Integrated End of List Listener for use of detecting when the user has scrolled to the bottom.
 * Maven Support.
 * Indicators to show the user when a Pull-to-Refresh is available.
 * Support for **ListFragment**!
 * Lots of [Customisation](https://github.com/chrisbanes/Android-PullToRefresh/wiki/Customisation) options!

Repository at <https://github.com/chrisbanes/Android-PullToRefresh>.


2.[android-Ultra-Pull-To-Refresh](https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh)

# Ultra Pull To Refresh

这是现在已经停止维护的下拉刷新项目的替代方案。继承于ViewGroup可以包含任何View。功能比SwipeRefreshLayout强大。

使用起来非常简单。良好的设计，如果你想定制自己的UI样式，非常简单，就像给ListView加一个Header View那么简单。

支持 `API LEVEL >= 8`。

[APK下载](https://raw.githubusercontent.com/liaohuqiu/android-Ultra-Pull-To-Refresh/master/ptr-demo.apk)

#### 下拉刷新 + 加载更多？

本类库是单纯的下拉刷新。如果你需要用到`加载更多`，看这个项目: https://github.com/liaohuqiu/android-cube-app

#### 使用eclipse的同学请注意, Intellij IDEA / Android Studio 请忽略

**demo可以直接在eclipse中运行, 编译demo项目的同学看这里:  http://www.liaohuqiu.net/cn/posts/compile-ultra-ptr-in-eclipse/**

* 先上两张StoreHouse风格的截图! 感谢 [CBStoreHouseRefreshControl](https://github.com/coolbeet/CBStoreHouseRefreshControl).
    <div class='row'>
        <img src='http://srain-github.qiniudn.com/ultra-ptr/store-house-string-array.gif' width="300px" style='border: #f1f1f1 solid 1px'/>
        <img src='http://srain-github.qiniudn.com/ultra-ptr/store-house-string.gif' width="300px" style='border: #f1f1f1 solid 1px'/>
    </div>

* 5.0 Material 风格 2014-12-09 新增。**阴影效果，gif图看起来有些失真，看demo吧！**
    <div class='row'>
        <img src='http://srain-github.qiniudn.com/ultra-ptr/material-style.gif' width="300px"/>
    </div>

* **支持所有的View**: 

    ListView, GridView, ScrollView, FrameLayout, 甚至 TextView.
    <div><img src='http://srain-github.qiniudn.com/ultra-ptr/contains-all-of-views.gif' width="300px" style='border: #f1f1f1 solid 1px'/></div>

* 支持各种下拉刷新交互.
    * 下拉刷新(iOS风格)
        <div><img src='http://srain-github.qiniudn.com/ultra-ptr/pull-to-refresh.gif' width="300px" style='border: #f1f1f1 solid 1px'/></div>

    * 释放刷新(经典风格)
        <div><img src='http://srain-github.qiniudn.com/ultra-ptr/release-to-refresh.gif' width="300px" style='border: #f1f1f1 solid 1px'/></div>

    * 刷新时，头部保持(新浪微博)

        <img src='http://srain-github.qiniudn.com/ultra-ptr/keep-header.gif' width="300px"/>

    * 刷新时，头部不保持(微信朋友圈)

        <img src='http://srain-github.qiniudn.com/ultra-ptr/hide-header.gif' width="300px" sytle='border: #f1f1f1 solid 1px'/>

    * 自动刷新，进入界面时自动刷新

        <img src='http://srain-github.qiniudn.com/ultra-ptr/auto-refresh.gif' width="300px" sytle='border: #f1f1f1 solid 1px'/></div>




