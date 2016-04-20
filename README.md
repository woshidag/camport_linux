# DEPTH CAMERA DEMO FROM PERCIPIO XYZ #

----------

This is a basic template for the users.

This directory implements a samll opencv2.4 based application. It gets depth or IR-grey data from the PERCIPIO's depth camera and shows it in windows.

## Code Structure ##

## root directory ##

camport_test.cpp: The entry point for the main program.

depth_render.cpp: .

depth_render.h: .

percipio_opencv_camport.h: .

## include directory ##

The include directory includes the relevant headers needed to call the dynamic library functions.

percipio_camport.h: introduce the data structure and api

## Usage ##

## Compiling the Code ##

First install the opencv2.4 releated package and the libusb (apt-get install libusb),

second, copy the libcamm.so to /usr/lib directory, and excute ldconfig to creates the necessary links and cache to the shared library.

run the make command to start compiling,

run sudo ./cam_test to show the xyz secret, enjoy it!
