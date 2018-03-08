# mwArray convert to QImage and Mat

- This project based on Qt, Matlab 2015b x86 and opencv.
- The Mat-QImage conversion is moved to [HERE](https://github.com/WangHongshuo/QImageMatConvert).  
## Introduction: ##
     
Mat-mwArray来源于互联网，QImage-mwArray是自己写的，可能有疏忽的地方。     
  
Mat-mwArray is obtained from the Internet, QImage-mwArray is created by myself, so it's unstable (       

## Change Log: ##

- 2018.01.09:     

Set this part to submodule.      

将该部分的转换独立为子模块。       

- 2018.01.08:      

Changed the variable names in `mat_qimage_convert` and added annotation. Tested all the function and fixed a small error.        

修改`mat_qimage_convert`中的变量名称，加入详细的说明，并对所有的转换进行了测试。修复了小错误。       

- 2017.12.16:

Updated` mat_qimage_convert.cpp` and now the Mat(QImage) can be converted to QImage(Mat) by deep copy(safer) or shallow copy(faster).

更新了 `mat_qimage_convert.cpp`，现在Mat和QImage可以用深拷贝（更安全）或浅拷贝（更快）的方式来进行转换。

- 2017.11.30:

Changed `cv::at` to `cv::ptr` in Mat-mwArray convert, but I didn't test it bucause I give up coding C++ with matlab.

将`Mat-mwArray`转换中`cv::at`访问改为`cv::ptr`访问，好像at比较慢，但是没有测试，因为我一个月前就放弃matlab混合编程了，太慢了

- 2017.11.13:

Added QImage-mwArray convert

添加QImage-mwArray转换


