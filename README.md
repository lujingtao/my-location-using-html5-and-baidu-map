@[toc](HTML5获取我的位置并在百度地图上显示)

# 一、前言
最近有兴趣研究了下移动端的地图api，发现其实挺简单的，HTML5也提供了地理位置API：Geolocation，能获取当前所在位置的经纬度，结合一些地图api，就能直观地看到我在地图上所在的位置，相当于app应用里面的“我的位置”。

在网上搜下Geolocation就能获得详细信息，其实核心就是这个：navigator.geolocation.getCurrentPosition(updateLocation, handleLocationError, options);

于是集合下网上的代码，做了个比较实用的demo(一开始用google，发现googleMapAPI.js被墙了，于是改用了百度)，位置精确度不是很高，日后再仔细研究下。

注意：
- <font color="red">1、必须使用https协议（包括页面内的所有链接）</font>
- 2、使用手机打开，并运行获得位置
- 3、最好用默认浏览器打开

# 二、在线演示和GitHub源码
效果：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20191015153000992.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2lhbWx1amluZ3Rhbw==,size_16,color_FFFFFF,t_70)
[-->在线演示地址](https://lujingtao.github.io/my-location-using-html5-and-baidu-map/)
[-->GitHub源码](https://github.com/lujingtao/my-location-using-html5-and-baidu-map)
