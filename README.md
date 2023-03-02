# bv-libs
存放为 [bv](https://github.com/aaa1115910/bv) 编译/修改过的依赖


## av1Decoder
Media 3 AV1 解码器

打包自 [Media 3 1.0.0-beta03](https://github.com/androidx/media/tree/c2cbb6370a265efc93661b659e70b2679506e995/libraries/decoder_av1)


## libVLC
去掉了 UserAgent 末尾强制加上的 `LibVLC/xxx`，并修改了加载 native lib 的路径

打包自 [VLC-Android](https://code.videolan.org/videolan/vlc-android/-/tree/a0f588afd3626fa1e97de81603c2589a9c62b004)

依赖版本 `3.6.0-ep05`，`LibVLC` 版本 `3.0.18`