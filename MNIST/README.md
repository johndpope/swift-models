# MNIST

This directory builds a two-layer perceptron to classify the [MNIST
dataset](http://yann.lecun.com/exdb/mnist/).

## Setup

To begin, you'll need the [latest version of Swift for
TensorFlow](https://github.com/tensorflow/swift/blob/master/Installation.md)
installed. Make sure you've added the correct version of `swift` to your path.
eg. 
````shell
which swift
/usr/bin/swift (this is the wrong path)
````
should be in the most updated toolchain path eg. 
/Library/Developer/Toolchains/swift-tensorflow-RELEASE-0.2.xctoolchain/usr/bin/swift


To train the model, run:

```
swift -O MNIST.swift
```
