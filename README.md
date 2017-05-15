# Cordova_InAppBrowser_Plugin_Example
Cordova插件`InAppBrowser`最常用使用场景是在**系统自带浏览器中打开APP内置链接**，该仓库为`InAppBrowser`使用案例。   

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