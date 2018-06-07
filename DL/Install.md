

## Install tensorflow,pytorch


1. install CUDA

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
  4.3. pip install --ignore-installed --upgrade tensorflow
  4.4  test installation of tensorflow:
    import tensorflow as tf
    hello = tf.constant('Hello, TensorFlow!')
    sess = tf.Session()
    print(sess.run(hello))
 ```
 
 5. [install pytorch](https://pytorch.org/)
  
  
  
```
