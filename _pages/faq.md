---
layout: page
title: FAQ
include_in_header: true
order: 1
---

# FAQ

## 车票识别

### 1. 为什么识别不出检票口？

12306 App“本人车票页”没有检票口信息，所以识别不到。

一般“订单详情页”会有检票口信息，可通过“订单详情页”来识别车票：订单详情页，点击右上角3个点 > 分享好友 > 弹出的分享浮层中找到“车票票” > 识别图中车票并添加。

后面计划与12306数据打通，除截图本身提供的信息外能够自动补充一些额外信息。

另外，临近发车时，车票顶部也会自动出现提示条，展示列车当前状态及检票口等信息。

### 2. 为什么有的截图明明有相关信息却识别不出来？

如果截图经过加工涂抹了部分信息，或截图分辨率较低，或使用了一些特殊字体，则会影响识别效果，建议对“铁路12306”App相关页面截图后不做处理直接分享到车票票进行识别。

另外，图片识别能力依赖于iOS系统，iOS 15的识别效果要弱于iOS 16，建议有条件的用户将系统升级到最新版本。

## 钱包

### 1. 车票添加到车票票了，怎么添加到钱包/日历呢？

未过期车票，左下角第1个按钮添加到日历，第2个按钮添加到钱包。已过期车票，左下角只有1个按钮，添加到钱包。

### 2. iPad找不到添加到钱包的入口

iPad系统没有钱包凭证功能，所以不支持将车票添加到钱包哦。可以使用iPhone录入车票并添加到钱包（车票左下角第2个图标），或者iPad录入车票后通过iCloud同步到登录同一个Apple ID的iPhone，然后再添加到钱包。

### 3. 为什么钱包凭证底部有一大片空白区域？

钱包凭证的整体样式是系统定义好的，底部这片区域用于展示二维码，但由于电子火车票的二维码是动态生成的，且其生成算法是不公开的，所以无法展示二维码也就留空了。

### 4. 车票添加到钱包后，4个字的车站显示不全（末尾打点）

怀疑是系统bug，有2个解决方案。

方案1：如使用的是“突出站名”的模板，可以编辑下车票，在4个字的站名后添加一个空格，然后再重新添加到钱包，系统会自动对字体进行缩放。

方案2：改为使用“突出时间”的模板。车票票设置 > 钱包凭证排版 > 突出时间。

### 5. 车票添加到钱包/日历后，我又手动修改了车票内容，但钱包/日历里的信息没有更新

手动修改车票内容后，再点击一下车票左下角的钱包/日历按钮，就可以更新啦。（后面会优化一下，修改车票内容后主动提示用户是否更新钱包/日历中的信息）

### 6. 车票添加到钱包后，锁屏界面没有展示

临近发车或在车站附近时，车票会自动展示在锁屏界面（具体展示条件由苹果系统决定）。

如满足上述条件，但车票仍未展示在锁屏界面，请打开钱包App，找到这张车票，点击右上角3个点菜单中的“凭证详细信息”，将“在锁定屏幕上显示”的开关打开。

### 7. 屏幕锁定时，锁屏界面查看车票详情需要解锁，有点不方便

请打开系统设置 > 面容ID与密码 > 锁定时允许访问，找到“钱包”，将开关打开。（页面比较长，选项在比较靠下的位置）

## 提醒

### 1. 为什么发车前没有收到提醒？

车票票、日历会在发车前3小时提醒用户，钱包会基于发车时间、所在位置在合适的时机提醒用户。

如果添加车票时距离发车时间已经不足3小时，那么车票票、日历就不会再提醒用户。

## 锁屏实时活动、灵动岛

### 1. 支持锁屏实时活动和灵动岛吗？

目前还不支持，不过已有相应计划。由于涉及到数据源、服务端推送、用户隐私等方面，一个人开发工作量较大，还请稍稍等待哦。
