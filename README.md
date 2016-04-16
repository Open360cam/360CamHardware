# The Open 360 Camera Hardware Repository 
[![Gitter](https://badges.gitter.im/Open360cam/360CamHardware.svg)](https://gitter.im/Open360cam/360CamHardware?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

This repository includes all details to build your own 360 degree spherical camera. Our design goals were to develop a DIY kit to build your own basic full 360 degree spherical camera. The hardware chosen for the kit is readily available off the shelf from the vendors listed below. The mechanical mounting components have been kept simple enough to assemble without any specialized tools or equipment. Cost has been minimized and balanced against providing reasonably good performance. This is a 2 camera fisheye design.  

To enable portable imaging, we have developed and tested the cameras on a Raspberry Pi 2 B+ utilizing OpenCV libraries to control and capture images from the cameras. The USB 2.0 cameras from ELP that we selected us the [Sonix SN9C292A](http://www.sonix.com.tw/article-en-995-7860) video controller with USB Video Class compatibility. 

Camera Specifications Full 360 Version:

* FOV 220 degrees per camera (Full image circle fits within image sensor frame)
* Resolution 2 x 5MP
* Board spacing 15mm
* Image sensor [OnSemi MI5100/MT9P10001](http://www.onsemi.com/pub_link/Collateral/MT9P001-D.PDF)
* Frame rate 15 fps full5 MP, 30 fps 1920x1080 Hd

Partial 360 Version Specifications:

* FOV 220 deg Horizontal, ~170 deg Vertical per camera
* Resolution 2 x5MP
* Board spacing 15mm
* Image sensor [OnSemi MI5100/MT9P10001](http://www.onsemi.com/pub_link/Collateral/MT9P001-D.PDF)
* Frame rate 15 fps full5 MP, 30 fps 1920x1080 Hd


Links and information:

* [Full 360 spherical costed BOM V 0.3](https://github.com/Open360cam/360CamHardware/blob/gh-pages/Full%20360%20BOMV0.03.csv)
* [Partial 360 spherical costed BOM V 0.3](https://github.com/Open360cam/360CamHardware/blob/gh-pages/Partial%20360%20BOM%20V0.3.csv) 
* [Delrin mount dimensions]( https://docs.google.com/drawings/d/1a1yqljNkfvwshJXSAQb4WQnTHRU0a6AmI5eeKOmlvyI/edit?usp=sharing)
* Instructions

Version 0.03 prototype
![V0.3](http://i.imgur.com/UVtXb0t.jpg?1)

