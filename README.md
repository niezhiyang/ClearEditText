# ClearEditText
带有清除按钮的EditText
## 首先看一下效果:
![这里写图片描述](https://github.com/niezhiyang/NGallery/blob/master/1495592800462~1.gif)
<br>
从图上可以看出, 两边的item可以被点击, 可以被滑动,也就是可以获得焦点
## demoapk位置:[demo.apk](https://github.com/niezhiyang/NGallery/blob/master/app-debug.apk)
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
