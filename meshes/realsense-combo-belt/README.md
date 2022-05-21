# Realsense Combo Belt

This adapter mates the comma body with the Intel-designed combo bracket for the T265 and D435 tracking and depth sensors.

### Software

You may find sample code in the [tracking-and-depth example in librealsense](https://github.com/IntelRealSense/librealsense/tree/master/examples/tracking-and-depth).

On the Comma 3, it's important to use `-DFORCE_RSUSB_BACKEND=ON` when compiling librealsense, otherwise the depth sensor won't work.

### Hardware

- Intel Realsense T265 
- Intel Realsense D435
- [Intel's bracket](https://github.com/IntelRealSense/librealsense/blob/master/examples/tracking-and-depth/bracket_t265nd435_external.stl)
- 2x M6x12 Bolt
- 2x M6 T-Slot Spring Nut