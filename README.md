# Groovy使用
## 1. 在项目目录下的build.gradle中添加
```
dependencies {
           classpath 'com.android.tools.build:gradle:2.1.0'
           classpath 'org.codehaus.groovy:gradle-groovy-android-plugin:0.3.6'
       }
```
## 2.在moudle下添加
```
apply plugin: 'groovyx.grooid.groovy-android'
```
## 以及dependencies
```
 compile 'org.codehaus.groovy:groovy-all:2.3.6'
```
## 以及android下
```
 lintOptions {
        disable 'InvalidPackage'
    }
```
### 关于android studio打开groovyconsole
在tools->groovyconsole