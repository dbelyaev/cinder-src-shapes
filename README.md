# cinder-scr-shapes
Simple Windows screensaver using Cinder framework with main purpose to re-create and old screensaver I saw many years ago on some Windows 98\XP machine. Was it called bouncing line or something?

![screnshot](screenshot.png)

# Build instuctions
* download latest [Cinder SDK](https://libcinder.org/download) (this project was tested with [v0.9.0](https://github.com/cinder/Cinder/tree/release_v0.9.0))
* add environment variable named `CINDERDIR` that points to where your Cinder installation folder is (for example: `c:\sdk\cinder`) 
* open solutions file at `.\shapes\vs2015\shapes.sln` and build it
* in `DEBUG` configuration project will be compiled as App (normal Window with controls), while in `RELEASE` it will generate Windows screensaver (exits on mouse events, fullscreen etc)