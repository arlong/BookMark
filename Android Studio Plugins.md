### Android Studio 常用插件

##### 1、Android相关
ADB Idea ADB操作快捷菜单，快速清除数据，重启应用，卸载应用等操作<br>
Android Annotations 配合Annotation框架快速生成控件绑定代码，同Android ButterKnife Zeleny ，本来都是用ButterKnife，生成快速绑定代码，后面开发的都是Lib库没办法使用ButterKnife只好转Annotations库<br>
Android Drawable Importer 做些小应用时妈妈再也不用担心我找不到图标了~需要配合google/material-design-icons · GitHub、Android Icons使用，安装后在设置菜单多出来的选项中设置<br>
Android Parcelable Code Generator 如标题。快速生成Parcelable代码<br>
Android Accessors 按照Google官方的开发规范，类的成员变量以m开头，此插件可快速生成成员变量的set/get方法但是不带m，评论中有人指出可以通过再Settings-CodeStyle-Java-CodeGeneration中修改前缀，经查验却是更加方便。<br>
SelectorChapek for Android 插件库好多生成Selector的插件，还是这个用的最顺，按照不同状态(normal、pressed)的标准命名后，右键文件树Generate Android Selectors见inmite/android-selector-chapek · GitHub<br>




##### 2、IntelliJ IDea通用
AceJump 快速跳转到屏幕某个位置（Ctrl+;）<br>
FindBugs-IDEA、CheckStyle-IDEA 用自动化代替双眼<br>
JavaDoc 添加注释，可自定义模板<br>
Eclipse Code Formmater 项目之前未全部转向Studio，该插件兼容Eclipse的代码格式化风格vv<br>
http://GrepCode.com Code Search 找源码必备~GrepCode IntelliJ Plugin<br>
RestClient 模拟HTTP请求测试与服务端的通讯请求，功能强大~<br>
Statistic  统计行数的插件<br>


莫装太多，小心卡顿，根据需求禁用部分插件。