# Cordova_InAppBrowser_Plugin_Example
Cordova插件[InAppBrowser](https://github.com/apache/cordova-plugin-inappbrowser)最常用使用场景是在**系统自带浏览器中打开APP内置链接**，该仓库为`InAppBrowser`使用案例。   

使用方法（使用前请确保已配置好Ionic工作环境）：   

1.将该仓库clone到本地：   

```bazaar
git clone git@github.com:xiaogliu/Cordova_InAppBrowser_Plugin_Example.git
```

2.添加Ionic使用平台（此处以安卓为例）   

```bazaar
ionic platfrom add android
```

3.构建APK   

```bazaar
ionic build android -release
```
4.设置签名，安装测试。   

（更详细信息可参考这边博文：[系统浏览器打开Ionic App内部链接(InAppBrowser)](http://xiaogliu.github.io/2017/05/15/%E7%B3%BB%E7%BB%9F%E6%B5%8F%E8%A7%88%E5%99%A8%E6%89%93%E5%BC%80Ionic-App%E5%86%85%E9%83%A8%E9%93%BE%E6%8E%A5-InAppBrowser/)）