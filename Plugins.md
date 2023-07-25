### 一、Android Studio 常用插件

##### 1、Android相关
* ADB Idea ADB操作快捷菜单，快速清除数据，重启应用，卸载应用等操作
* Android Annotations 配合Annotation框架快速生成控件绑定代码，同Android ButterKnife Zeleny ，本来都是用ButterKnife，生成快速绑定代码，后面开发的都是Lib库没办法使用ButterKnife只好转Annotations库
* Android Drawable Importer 做些小应用时妈妈再也不用担心我找不到图标了~需要配合google/material-design-icons · GitHub、Android Icons使用，安装后在设置菜单多出来的选项中设置
* Android Parcelable Code Generator 如标题。快速生成Parcelable代码
* Android Accessors 按照Google官方的开发规范，类的成员变量以m开头，此插件可快速生成成员变量的set/get方法但是不带m，评论中有人指出可以通过再Settings-CodeStyle-Java-CodeGeneration中修改前缀，经查验却是更加方便。
* SelectorChapek for Android 插件库好多生成Selector的插件，还是这个用的最顺，按照不同状态(normal、pressed)的标准命名后，右键文件树Generate Android Selectors见inmite/android-selector-chapek · GitHub
* Jrebel for android [官网](https://zeroturnaround.com/software/jrebel-for-android/) Android Studio 快速编译插件替代Instant Run，收费的(网上有破解版，[最新破解版获取](http://blog.lanyus.com/archives/179.html))，非常好用
* Android Postfix Completion 可根据后缀快速完成代码，这个属于拓展吧，系统已经有这些功能，如sout、notnull等
* BorePlugin [链接](https://github.com/boredream/BorePlugin) Android Studio 自动生成布局代码插件




##### 2、IntelliJ IDea通用
* AceJump 快速跳转到屏幕某个位置（Ctrl+;）<br>
* FindBugs-IDEA、CheckStyle-IDEA 用自动化代替双眼<br>
* JavaDoc 添加注释，可自定义模板<br>
* Eclipse Code Formmater 项目之前未全部转向Studio，该插件兼容Eclipse的代码格式化风格vv<br>
* Code Search [官网](http://GrepCode.com) 找源码必备~GrepCode IntelliJ Plugin<br>
* RestClient 模拟HTTP请求测试与服务端的通讯请求，功能强大~<br>
* Statistic [地址](http://plugins.jetbrains.com/plugin/?idea&id=4509)  统计行数的插件<br>


莫装太多，小心卡顿，根据需求禁用部分插件。



### 二、其他插件
##### 收集的Plugin
* [jiang111/awesome-androidstudio-plugins (收集Android studio 常用的插件)](https://github.com/jiang111/awesome-androidstudio-plugins)
* [dmytrodanylyk/folding-plugin (AS文件分组显示)](https://github.com/dmytrodanylyk/folding-plugin)
* [FelisCatus/SwitchyOmega (Chrome代理插件)](https://github.com/FelisCatus/SwitchyOmega)
* [buunguyen/octotree (树形展示Github项目代码)](https://github.com/buunguyen/octotree)
* [Sourcegraph (Github项目代码像IDE上常用的功能操作)](https://link.jianshu.com/?t=https://chrome.google.com/webstore/detail/sourcegraph-for-github/dgjhfomjieaadpoljlnidmbgkdffpack)
* [carlospaulino/parrot (string资源翻译成其他其他语言的 Gradle 插件)](https://github.com/carlospaulino/parrot)
* [Skykai521/ECTranslation (英文翻译插件，基于有道开放API)](https://github.com/Skykai521/ECTranslation)
* [Insight.io for Github (最好的GitHub代码浏览插件)](https://chrome.google.com/webstore/detail/insightio-for-github/pmhfgjjhhomfplgmbalncpcohgeijonh/) [<u>说明地址</u>](http://www.geeksense.cn/plugin/?utm_source=androidweekly.cn&utm_medium=website)
