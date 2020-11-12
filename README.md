# 编译opencv注意事项
### 1.先新建一个build文件，用来存放编译后的文件 

### 2.camke编译    
  >a.第一项是勾选BUILD_opencv_world选项，这样，在调用dll时，只调用这一个就行了，不用根据功能选择了，省了些麻烦。  
  >b.第二项，在OPENCV_EXTRA_MODULES_PATH选项中，填写opencv_contrib解压目录下，modules文件夹的路径，这样就把opencv_contrib编译进去了。  
  >c.增加勾选OPENCV_ENABLE_NONFREE  
  >d.configure  
  >f.generate 
  
### 3.VS打开OpenCV.sln  
  >ALL_BUILD->生成  
  >INSTALL->点击“仅用于项目->仅生成INSTALL”  
