# Yuneec-RTSP-Player-Android
Android Library for displaying live video stream from camera. This library uses [IJKPlayer](https://github.com/Bilibili/ijkplayer), which is based on [FFmpeg](http://ffmpeg.org/). 

## Usage

### Pull in using maven

To use this library in your Android application, you can add the following to the root `build.grade`:

```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

Then, add the dependency to the app's `build.gradle`:

```
compile 'com.github.YUNEEC:Yuneec-RTSP-Player-Android:X.Y.Z'
```
where X.Y.Z is the version to select.

To see all the available versions, go to [Jitpack](https://jitpack.io). In the look up box paste YUNEEC/Yuneec-RTSP-Player-Android.

Please choose the latest version of the library to integrate with your project.

## Tutorial

For more details on usage of this library, please refer https://developer.yuneec.com/documentation/120/Live-Video-Streaming.

## License 

The source code in this repository is published under the [BSD 3-Clause license](LICENSE).

Yuneec-RTSP-Player-Android uses libraries of IJKPlayer licensed under the LGPLv2.1. The source code of these libraries, the compilation instructions, and the LGPL v2.1 license are provided in [Github](https://github.com/YUNEEC/videostreamplayer).
