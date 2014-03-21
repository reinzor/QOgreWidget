QOgreWidget
===========

QOgreWidget is a QT5 (Desktop) Widget that embeds the Ogre3D graphics engine. Currently it builds and rund on Linux and Windows7.

Linux
-----
prerequisites:
* OGRE 1.9
* boost

configure, build and run the example:
* run ./configure.sh to configure
* run ./build.sh to build
* after build, you can run the demo QOgreWidgetDemo

Windows
-------
prerequisites:
* install OGRE 1.9 SDK for Visual C++ 2010 32-bit
* install Qt 5.2.1 for Windows 32-bit (VS 2010, OpenGL)
* The environment variable OGRE_HOME must point to the OGRE SDK

configure, build and run the example:
* run ./configure.bat to configure
* open the generated Visual Studio 2010 solution file located in the build directory
* after build (just building the "Release" version is supported), you can run the demo QOgreWidgetDemo.exe

for more info also look [here](http://whimdump.net/blog/?p=111)
