# Deep Learning	Vagrant	Machine

These Vagrant files automates the installation of a working Deep Learning machine running on Ubuntu 14.04.

What's in the box:
* Keras
* Theano
* Tensorflow

# Requirements

* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

* [Vagrant](https://www.vagrantup.com/downloads.html)

You must install VirtubalBox and Vagrant before continuing.

# Getting started

Once Vagrant and VirtualBox are installed, clone this repository or import `Vagrantfile` and `bootstrap.sh` in a directory.

From this directory, let's initiate your Vagrant box by typing in your terminal (it makes time some time to download the Ubuntu image):
    
    $ vagrant init
And let's start	your Vagrant box:
    
    $ vagrant up
Once the setup is complete, just run:
    
    $ vagrant ssh
You are in! Now, let's train your first neuronal network:

    $ python keras/examples/addition_rnn.py

# Documentation

* [Keras](http://keras.io/)
* [Theano](http://deeplearning.net/software/theano/)
* [TensorFlow](https://www.tensorflow.org/versions/r0.7/api_docs/index.html)