# Android-IOS-Pjsip-Compile-Script

Pjsip库编译脚本，一行命令编译Android/IOS下的.so库和.a库。

### 为Android编译.so库

将build-android拷贝到pjsip的根目录中，检查里面的ndk路径是否正确，运行下面的命令开始编译，生成的so库在pjsip-apps/src/swig/java/android/app/src/main/jniLibs/armeabi下。

```sh
chmod 777 build-android
./build-android
```

### 为Iphone编译.a库

将build-iphone拷贝到pjsip的根目录中，运行下面的命令开始编译，生成的.a库在lib目录下。

```sh
chmod 777 build-iphone
./build-iphone
```

