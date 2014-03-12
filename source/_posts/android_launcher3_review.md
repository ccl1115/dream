title: Android kitkat new launcher app source review
date: 2014-01-15 11:59:52
tags: android
---

介绍
====

随着Android 4.4 Kitkat版本的发布，Android也引来了它的第三代Launcher。如果说从一代到二代变化得最多的就是应用抽屉，那么从二代到三代变化得最大的就算桌面部分了。随着屏幕的变大，新Launcher在长按桌面之后会进入另一种模式，可以更加方便的添加widget，修改壁纸，以及调整分页的顺序。而当一个分页没有任何内容的时候就会被自动的从桌面移除。这种变化使得用户不用担心5个分页太多，或者不够用了，不喜欢把图标或者widgets放到桌面的用户只会有一到两个分页，而喜欢往桌面放各种漂亮widgets的人，理论上新版Launcher是可以扩展无限个桌面分页的。

代码结构
========
