# ClearEditText
带有清除按钮的EditText
##效果图

![这里写图片描述](opts_chunk$set(width=300, height=600)http://img.blog.csdn.net/20170719163055592?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvcXFfMzM0MDgyMzU=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
## 使用方式
### 添加依赖
1.在根目录的build.gradle中添加

	allprojects {
    repositories {
        jcenter()
        maven { url 'https://jitpack.io' }// 添加jitpack.依赖
    }
2.在app的build.gradle中添加

		compile 'com.github.niezhiyang:ClearEditText:1.0'
3.在xml中直接写ClearEditText就可以了 用法跟EditText完全一样
