# TFT-ML-Week-4

## Assignment  
Coach: [Yiqi](https://saoyan.github.io/)  

Build a convolutional neural network for CIFAR-10 classification task.  

* Download data
  * Use the following code  
  ```
  import cifar10
  cifar10.maybe_download_and_extract()
  ```
  * If the downloading code is blocked for internet connection proboem, [download the data here](https://drive.google.com/open?id=1VTZgZRDh1PS3EtKNjeSq29pOkVGLLR2F). Extract it at the same path as the scripts.  

* Build CNN model  
  * First of all, make sure you understand the basic building blocks of CNNs (convolutional layer, pooling layer). [Here is a good reading material.](http://cs231n.github.io/convolutional-networks/)  
  * The next step is to understand how convolutional layer and pooling layer are implemented in Tensorflow. [tf.nn.conv2d](https://www.tensorflow.org/api_docs/python/tf/nn/conv2d); [tf.nn.max_pool](https://www.tensorflow.org/api_docs/python/tf/nn/max_pool)
