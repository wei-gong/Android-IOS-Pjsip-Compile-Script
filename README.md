# PJSIP-Android-Compile-Script

Pjsip库Android平台编译脚本，一行命令编译Pjsip for Android。

###使用方法

将build-android拷贝到pjsip的根目录中，检查里面的ndk路径是否正确，直接运行即可。

生成的so库在pjsip-apps/src/swig/java/android/app/src/main/jniLibs/armeabi下。

```sh
chmod 777 build-android
./build.sh
```

