# sfplay
===

A very basic video player that is mostly just a testing ground for the ffmpeg API.

Some features include:

* Compatibility with all ffmpeg file formats and codecs
* Smooth and synched video/audio streams using clocks
* Video and audio output using SDL
* Rudimentary seeking

### Dependencies

This project requires that you have libavformat, libavcodec and sdl-config installed
-------
```
gcc -o sfplay sfplay.c -lavformat -lavcodec -lswscale -lz -lm `sdl-config --cflags --libs`
```

### Running
-------

```
sfplay myvideofile.mpg
```

Where myvideofile.mpg is any video file of your choice :)