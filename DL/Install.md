

## install tensorflow,pytorch

```
1. install CUDA
2. install Anaconda

3. install tensorflow
  3.1  conda create -n tensorflow pip python=3.5 
  3.2  activate tensorflow
  3.3. pip install --ignore-installed --upgrade tensorflow

4. pip install jupyter notebook
5. jupyter notebook
6. Create a notebook and type in Hello World:
  import tensorflow as tf
  hello = tf.constant('Hello, TensorFlow!')
  sess = tf.Session()
  print(sess.run(hello))
```
