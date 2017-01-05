Android Things GPIO Benchmarking
================================

This project aims to benchmark gpio operations

This version shows the following results on a RPI3.

Method A / Java
---------------
- java manual toggling from true to false as low as 3KHZ.
- java inverting as low as 1 KHZ.

Method B / Native C++
---------------------
...dev pendings...

Pre-requisites
--------------

- Android Things compatible board
- Android Studio 2.2+


Build and install
=================

On Android Studio, click on the "Run" button.

If you prefer to run on the command line, type

```bash
./gradlew installDebug
adb shell am start com.example.androidthings.myproject/.MainActivity
```

