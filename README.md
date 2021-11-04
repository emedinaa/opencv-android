# opencv-android
Opencv for android developers

1. Abrir proyecto con Android Studio 4.2.2

https://developer.android.com/studio/
https://developer.android.com/studio/archive

2. Instalar NDK y agregar el path en *local.properties*

```
ndk.dir=<user path>/Library/Android/sdk/ndk/21.2.6472646
```

3. Generar aar de opencv

```
./gradlew :opencv:assembleRelease
```

Se va a generar el aar en el folder **OpenCV-android-sdk/sdk/build/outputs/aar/opencv.aar**