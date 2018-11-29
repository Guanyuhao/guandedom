### 360
```
<!-- 选择使用的浏览器解析内核 -->
<meta name="renderer" content="webkit|ie-comp|ie-stand">
```
### chmore
```
<!-- 优先使用最新的chrome版本 -->
<meta http-equiv="X-UA-Compatible" content="chrome=1" />
<!-- 禁止自动翻译 -->
<meta name="google" value="notranslate">
```
### viewport
```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
content 参数：
 width viewport 宽度(数值/device-width)
 height viewport 高度(数值/device-height)
 initial-scale 初始缩放比例
 maximum-scale 最大缩放比例
 minimum-scale 最小缩放比例
 user-scalable 是否允许用户缩放(yes/no)
```
### IE
```
<!-- 优先使用最新的ie版本 -->
<meta http-equiv="x-ua-compatible" content="ie=edge">
<!-- 是否开启cleartype显示效果 -->
<meta http-equiv="cleartype" content="on">
<meta name="skype_toolbar" content="skype_toolbar_parser_compatible">


<!-- Pinned Site -->
<!-- IE 10 / Windows 8 -->
<meta name="msapplication-TileImage" content="pinned-tile-144.png">
<meta name="msapplication-TileColor" content="#009900">
<!-- IE 11 / Windows 9.1 -->
<meta name="msapplication-config" content="ieconfig.xml">
```
### SEO
```
<!-- 页面标题<title>标签(head 头部必须) -->
<title>your title</title>
<!-- 页面关键词 keywords -->
<meta name="keywords" content="your keywords">
<!-- 页面描述内容 description -->
<meta name="description" content="your description">
<!-- 定义网页作者 author -->
<meta name="author" content="author,email address">
<!-- 定义网页搜索引擎索引方式，robotterms 是一组使用英文逗号「,」分割的值，通常有如下几种取值：none，noindex，nofollow，all，index和follow。 -->
<meta name="robots" content="index,follow">
```
### 移动端
```
<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="apple-mobile-web-app-status-bar-style" content="black" />
<meta name="format-detection"content="telephone=no, email=no" />
<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
<meta name="apple-mobile-web-app-capable" content="yes" /><!-- 删除苹果默认的工具栏和菜单栏 -->
<meta name="apple-mobile-web-app-status-bar-style" content="black" /><!-- 设置苹果工具栏颜色 -->
<meta name="format-detection" content="telphone=no, email=no" /><!-- 忽略页面中的数字识别为电话，忽略email识别 -->
<!-- 启用360浏览器的极速模式(webkit) -->
<meta name="renderer" content="webkit">
<!-- 避免IE使用兼容模式 -->
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<!-- 针对手持设备优化，主要是针对一些老的不识别viewport的浏览器，比如黑莓 -->
<meta name="HandheldFriendly" content="true">
<!-- 微软的老式浏览器 -->
<meta name="MobileOptimized" content="320">
<!-- uc强制竖屏 -->
<meta name="screen-orientation" content="portrait">
<!-- QQ强制竖屏 -->
<meta name="x5-orientation" content="portrait">
<!-- UC强制全屏 -->
<meta name="full-screen" content="yes">
<!-- QQ强制全屏 -->
<meta name="x5-fullscreen" content="true">
<!-- UC应用模式 -->
<meta name="browsermode" content="application">
<!-- QQ应用模式 -->
<meta name="x5-page-mode" content="app">
<!-- windows phone 点击无高光 -->
<meta name="msapplication-tap-highlight" content="no">
<!-- 适应移动端end -->
 
```
