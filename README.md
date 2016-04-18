# The Open 360 Camera Hardware Repository 
[![Gitter](https://badges.gitter.im/Open360cam/360CamHardware.svg)](https://gitter.im/Open360cam/360CamHardware?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Version 0.02 prototype 
![](http://i.imgur.com/UVtXb0tm.jpg?1)

This repository includes all details to build your own 360 degree spherical camera. Our design goals were to develop a DIY kit to build your own basic full 360 degree spherical camera. The hardware chosen for the kit is readily available off the shelf from the vendors listed below. The mechanical mounting components have been kept simple enough to assemble without any specialized tools or equipment. Cost has been minimized and balanced against providing reasonably good performance. This is a 2 camera fisheye design.  

To enable portable imaging, we have developed and tested the cameras on a Raspberry Pi 2 B+ utilizing OpenCV libraries to control and capture images from the cameras. The USB 2.0 cameras from ELP that we selected us the [Sonix SN9C292A](http://www.sonix.com.tw/article-en-995-7860) video controller with USB Video Class compatibility. 

**If there is enough interest in this project, we will consider organizing a bulk buy of the kit parts to save on shipping costs Please log your interst on the Gitter chat.**

Camera Specifications Full 360 Version:

* FOV 220 degrees per camera (Verified through optical measurements that between 206 and 212 degrees fits within full active arrea 1452 pixels)
* Resolution 2 x 5MP
* Board spacing 15mm
* Image sensor [OnSemi MI5100/MT9P10001](http://www.onsemi.com/pub_link/Collateral/MT9P001-D.PDF)
* Frame rate 15 fps full5 MP, 30 fps 1920x1080 Hd

![](https://docs.google.com/drawings/d/1qfG-w03bYuRvKSpJNDEqPN0JQ_ewQdfzTyqCp624rVs/pub?w=480&h=360)

_Nearly_ 360 Version Specifications:

This option is included since you can purchase the 5MP sensor with a 180degree stock lens option for just a little more than a basic stock lens. 

* FOV 180 deg Horizontal X 150 deg Vertical per camera (1.56mm Stock lens shipped with ELP-USB500W05G-L180)
* Resolution 2 x 5MP
* Board spacing 15mm
* Image sensor [OnSemi MI5100/MT9P10001](http://www.onsemi.com/pub_link/Collateral/MT9P001-D.PDF)
* Frame rate 15 fps full5 MP, 30 fps 1920x1080 Hd

![](https://docs.google.com/drawings/d/1Y7bsweQgcvMa-xUnCi001ipqLVIXz2fOsW-fbs8W32I/pub?w=480&h=360)

Repository files:

* Full 360 spherical BOM [Full 360 BOM V0.3.csv](https://github.com/Open360cam/360CamHardware/blob/gh-pages/Full%20360%20BOM%20V0.3.csv)
* Partial 360 spherical BOM [Partial 360 BOM V0.3.csv](https://github.com/Open360cam/360CamHardware/blob/gh-pages/Partial%20360%20BOM%20V0.3.csv) 
* Mount hole patern: [BaseMountRev1.dxf](https://github.com/Open360cam/360CamHardware/blob/gh-pages/BaseMountRev1.dxf)
* Instructions



