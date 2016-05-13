# The Open 360 Camera Hardware Repository 
[![Gitter](https://badges.gitter.im/Open360cam/360CamHardware.svg)](https://gitter.im/Open360cam/360CamHardware?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

[On hackaday.io](https://hackaday.io/project/11604-360-camera)

***

Version 0.2 prototype 

[View on Google Stree View](https://www.google.com/maps/@43.8062169,-70.2512689,3a,90y,332.7h,82.47t/data=!3m7!1e1!3m5!1s-5MO35BMW5HE%2FVyUo9E1VHvI%2FAAAAAAAAHNw%2FE2HV6cnC8mYH1FQPFqYaJbeJtALE0PSlgCLIB!2e4!3e12!7i2172!8i1086)
![](http://i.imgur.com/UVtXb0tm.jpg?1) ![](http://i.imgur.com/9lv8rzXm.jpg)![](http://i.imgur.com/TNTswUMl.jpg)



More details on image capture in the [wiki](https://github.com/Open360cam/360CamHardware/wiki/Field-Testing) and the [360CamCode Repository](https://github.com/Open360cam/360CamCode)

***
## About
The entrance of consumer grade and professional 360 spherical cameras to the market will change the way people capture and interact with digital images and video.  While cameras like the Ricoh Theta, Samsung Gear 360 and Facebook Surround 360 cameras will meet consumer and professional needs, no platform is available to the maker, hacker, or educator.  

This goal of this project is to develop a hardware kit that is open, hackable, adaptable, and extensible to open this incredible technology to everyone.  

This repository includes all the details to build your own 360 degree spherical camera. The goal of this project is to develop a kit to for a DIY 360 degree spherical camera. 

Our key principals are as follows:
* Open source hardware and software to encourage educational use and a developer community
* The primary hardware is to be off the shelf (lenses and image sensor PCBs)
* Simple mechanical mounting, can be assembled without any specialized tools or equipment
* Compatible with mobile computing platforms such as Raspberry Pi or similar
* Cost to be similar to a consumer level 360 camera such as Ricoh Theta ($250-$350)
* Performance to be adequate to create 360 panoramas 

To enable portable imaging, we have developed and tested the cameras on a Raspberry Pi 2 B utilizing OpenCV libraries to control and capture images from the cameras. The USB 2.0 cameras from ELP that we selected us the [Sonix SN9C292A](http://www.sonix.com.tw/article-en-995-7860) video controller with USB Video Class compatibility. 

**If there is enough interest in this project, we will consider organizing a bulk buy of the kit parts to save on shipping costs Please log your interest on the Gitter chat.**

Camera Specifications Full 360 Version:

* FOV 220 degrees per camera (Verified through optical measurements that between 206 and 212 degrees fits within full active area 1452 pixels)
* Resolution 2 x 5MP
* Board spacing 15mm
* Image sensor [OnSemi MI5100/MT9P10001](http://www.onsemi.com/pub_link/Collateral/MT9P001-D.PDF)
* Frame rate 15 fps full5 MP, 30 fps 1920x1080 Hd

![](https://docs.google.com/drawings/d/1qfG-w03bYuRvKSpJNDEqPN0JQ_ewQdfzTyqCp624rVs/pub?w=480&h=360)

_Nearly_ 360 Version Specifications:

This option is included since you can purchase the 5MP sensor with a 180degree stock lens option for just a little more than a basic stock lens. Because the image quality is low at the edge of the image, you would likely need 3-4 of these to achieve usable images.

* FOV 185 deg Horizontal X 154 deg Vertical per camera (1.56mm Stock lens shipped with ELP-USB500W05G-L180)
* Resolution 2 x 5MP
* Board spacing 15mm
* Image sensor [OnSemi MI5100/MT9P10001](http://www.onsemi.com/pub_link/Collateral/MT9P001-D.PDF)
* Frame rate 15 fps full5 MP, 30 fps 1920x1080 Hd

![](https://docs.google.com/drawings/d/1Y7bsweQgcvMa-xUnCi001ipqLVIXz2fOsW-fbs8W32I/pub?w=480&h=360)

Repository files:

* Full 360 spherical BOM [Full 360 BOM V0.3.csv](https://github.com/Open360cam/360CamHardware/blob/gh-pages/Full%20360%20BOM%20V0.3.csv)
* Partial 360 spherical BOM [Partial 360 BOM V0.3.csv](https://github.com/Open360cam/360CamHardware/blob/gh-pages/Partial%20360%20BOM%20V0.3.csv) 
* Mount hole pattern: [BaseMountRev1.dxf](https://github.com/Open360cam/360CamHardware/blob/gh-pages/BaseMountRev1.dxf)
* Instructions



