

## Install tensorflow,pytorch


1. install CUDA: [於Win10環境下配置CUDA 9.0與cuDNN 7.0](https://rreadmorebooks.blogspot.com/2018/01/win10cuda-90cudnn-70.html)

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
