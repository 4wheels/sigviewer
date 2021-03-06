SigViewer
=========

SigViewer is a viewing application for biosignals.

Building SigViewer
------------------

SigViewer depends on the following external libraries:

- [Qt4](http://qt-project.org/)
- [libbiosig](http://biosig.sourceforge.net/)

General instructions:

1. Install Qt4 development packages
2. Download the "external" archive for your platform from http://sigviewer.sourceforge.net/
3. Extract the "external" archive into SigViewer's source folder (the folder where "sigviewer.pro" is located)
4. Use qmake to generate a Makefile and call make:


    qmake sigviewer.pro && make

The SigViewer binary can be found in the "bin" directory (release or debug subfolders)

Deploying SigViewer
-------------------

Debian/Ubuntu:
  1. Build SigViewer
  2. Run the script "build-deb.sh", which generates a .deb package:


    ./build-deb.sh
