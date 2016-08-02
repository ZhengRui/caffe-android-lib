## Caffe-Android-Lib


+ This is a fork of [sh1r0/caffe-android-lib](https://github.com/sh1r0/caffe-android-lib). For installation, check the `sh1r0/caffe-android-lib`.

+ Changes:
    * Inputs to jni part are mainly `Mat` from `opencv`, rather than file path.
    * Can load multiple models, use conventional pointers rather than a static member to locate each model.
    * support batch forwarding for feature extraction, and only forward to the layers of interests. Both batch processing and not forwarding to fully connected layers save computations and time.

+ TODO: demo android apps will be added soon.
