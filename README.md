# OpenCVDemo
OpenCVDemo
1,导入Opencv.framwork的时候要使用拖拽的方式进行导入  并且选择复制framwork到项目
 若是使用 add File to "xxxx "  会报find not  opencv2 的问题  我遇到的大坑

2, 引入头文件的时候要把头文件放在#import "ViewController.h"上面   
  若不放在上面会出现错误:
opencv2.framework/Headers/stitching/detail/exposure_compensate.hpp:65:12: Expected identifier


3, .该库不支持 bitcode 用之前要记得关闭,否则无法通过编译



4, 需要引入头文件的类要修改后缀为.mm

https://www.jianshu.com/p/7f615f11437d







