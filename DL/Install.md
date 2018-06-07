

## Install Visual Studio 2017, CUDA,python, tensorflow, pytorch on Windows 10

1. download and install [Visual Studio 2017 community](https://www.visualstudio.com/downloads/)

2. [install CUDA](https://docs.nvidia.com/cuda/cuda-installation-guide-microsoft-windows/index.html)

[於Win10環境下配置CUDA 9.0與cuDNN 7.0](https://rreadmorebooks.blogspot.com/2018/01/win10cuda-90cudnn-70.html)
  
[Windows 10 安装使用TensorFlow-GPU cuda 9.0](https://www.codetd.com/article/147955)
  
   - 1.0 uninstall CUDA 8. [卸载以前安装的CUDA8](https://blog.csdn.net/shuiyuejihua/article/details/78738664)
   
   - 1.1 download Cuda 9.0 . [下载CUDA9.0](https://developer.nvidia.com/cuda-90-download-archive)  :注意除“ Base Installer”外，所有“patch”都要下载
   - 1.2 download Cudnn7.0并解压到C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.0
   
   - 1.3 install CUDA9.0 安装CUDA9 （注意：先要安装VS2017） 

 

3. [install Anaconda](https://www.anaconda.com/download/)



4. [install tensorflow](https://www.tensorflow.org/install/)
```
  4.1  conda create -n tensorflow pip python=3.5 
  4.2  activate tensorflow    
       conda activate tensorflow
  4.3. 
  CPU版本：  pip install --ignore-installed --upgrade tensorflow
  或GPU版本： pip install --ignore-installed --upgrade tensorflow-gpu 
  
  4.4 pip install jupyter notebook
    jupyter notebook
    
  4.5  test installation of tensorflow:
    import tensorflow as tf
    hello = tf.constant('Hello, TensorFlow!')
    sess = tf.Session()
    print(sess.run(hello))
    
   4.6 deactive tensorflow 
       conda deactive tensorflow
 ```
 
 5. [install pytorch](https://pytorch.org/) 和[Creating Conda Environments](https://dziganto.github.io/data%20science/python/anaconda/Creating-Conda-Environments/)

```
  5.1 conda create -n pytorch  python=3.6 numpy scipy  cython
  5.2 activate pytorch
  5.3  conda install pytorch cuda90 -c pytorch 
      pip install torchvision
      pip install jupyter notebook
  5.4  jupyter notebook
  5.5 in your notebook,test following code:
    
  
        from __future__ import print_function
        import torch
        x = torch.empty(5, 3)
        print(x)
    
 ```   
  
