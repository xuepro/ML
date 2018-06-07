

## Install tensorflow,pytorch



1. [install CUDA](https://docs.nvidia.com/cuda/cuda-installation-guide-microsoft-windows/index.html)

  [於Win10環境下配置CUDA 9.0與cuDNN 7.0](https://rreadmorebooks.blogspot.com/2018/01/win10cuda-90cudnn-70.html)
  
  [Windows 10 安装使用TensorFlow-GPU cuda 9.0](https://www.codetd.com/article/147955)
  
   1.0 [卸载以前安装的CUDA8](https://blog.csdn.net/shuiyuejihua/article/details/78738664)
   
   1.1 [下载CUDA9.0](https://developer.nvidia.com/cuda-90-download-archive)  :注意除“ Base Installer”外，所有“patch”都要下载
   
   1.2 安装CUDA9 （注意：先要安装VS2017） 

 

2. install Anaconda

3. install jupyter 
```
    pip install jupyter notebook
    jupyter notebook
```

4. [install tensorflow](https://www.tensorflow.org/install/)
```
  4.1  conda create -n tensorflow pip python=3.5 
  4.2  activate tensorflow
  4.3. 
  CPU版本：  pip install --ignore-installed --upgrade tensorflow
  或GPU版本： pip install --ignore-installed --upgrade tensorflow-gpu 
  
  4.4  test installation of tensorflow:
    import tensorflow as tf
    hello = tf.constant('Hello, TensorFlow!')
    sess = tf.Session()
    print(sess.run(hello))
 ```
 
 5. [install pytorch](https://pytorch.org/) 和[Creating Conda Environments](https://dziganto.github.io/data%20science/python/anaconda/Creating-Conda-Environments/)
  
  
  
```
