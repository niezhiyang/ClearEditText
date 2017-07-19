# ClearEditText
带有清除按钮的EditText
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
