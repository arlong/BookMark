### 一、Gradle Samples

* gradle-samples-0.14.4 [下载地址](http://isming.qiniudn.com/gradle-samples-0.14.4.zip) <br>


### 二、Gradle 示例
1、MakeJar
```gradle
task makeJar(type:Jar){
    baseName = 'XXX'//生成jar包名字
    extension = 'jar'//扩展名

    from('build/intermediates/classes/debug/')
    include 'XXX/XXX/XXX/**'//包含的部分
    exclude '**/BuildConfig.class'//不包含的类
    exclude '**/R.class'
    exclude '**/R\$*.class'
}
makeJar.dependsOn(build)
```
