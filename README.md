# NeuralNetTutorial

![web net](web.jpeg)

Introduction to Keras and Tensorflow for lab projects.
*****
### Hello! 

If you're here, you're probably a member of the Hamilton lab and you probably want or need to figure out how to use neural networks for your projects. Great! This repo will provide you with everything you need to get started. 

*****

## Getting Started 
### Requirements and Instalation 

Everything we'll be doing requires python 3.6 and requires some extra modules you may not have.  
To work with these examples, you're going to need some of the following modules on your machine:

* __Numpy__ - This is python's linear algebra package.
* __Tensorflow__ (`tf`) - Google's machine learning library (Extensive and powerful, but takes some time to master).
* __Keras__ - High level neural net library that uses Tensorflow backend (Almost as flexible as `tf`, but far easier to get up and running).

If you don't have these, they can be installed several ways.

I'd recommend getting Anaconda and creating a conda environment with these packages. Anaconda is a package manager useful for scientific computing.  
_[More on getting Anaconda](https://www.anaconda.com/distribution/)._

**Note:** It is necessary to install both Keras and Tensorflow for this notebook, but you'll use only one. Using the tensorflow module `tf.keras`  is almost identical to standalone `keras`, though the `tf.keras` uses slightly different stuff under the hood. You can use either one to run the examples in this notebook, but I'd reccomend `keras` for now.  Once you get the hang of keras, you can move on to or even combine it with regular tensorflow if you want to do something really fancy! 
*****
### After you install anaconda, you'll run something like this in your terminal:  
`conda create -n tensorflow_env tensorflow keras`   _* mind the spaces!_   
   
Here, `-n` is the name creation flag, `tensorflow_env` is the name of the environment passed to `-n`, and `tensorflow` and `keras` are the primary packages being installed. Anaconda will grab everything else you need to make these work!  
You can use any name you want for your environment by swapping `tensorflow_env` with `your_env_name`.

_* For more on installing tensorflow with anaconda, follow the instructions [here](https://www.anaconda.com/tensorflow-in-anaconda/)._ 

__Note:__ You may have to up- or down-grade the `tf` version. As of this writing, the stable versions are 1.12 or 1.13, but 2.0 has been rolled out. This isn't too big of an issue as we'll be using Keras anyway, and we only need a compatable version of tensorflow to work with Keras.  If you need to do so, replace `tensorflow` with `tesnorflow==1.12`  
*****
### To activate your environment, run:  
`conda activate tensorflow_env`
  
When active, your terminal will look something like:  
    
`(my_env_name) userid:/cur/open/path$` 
*****
### Then set the correct python version:  

`conda install python==3.6`  

_* You can use pip instead of conda here._
    
_* Make sure pip is up to date!!!_

For everyting you'll ever need on Keras, check out [this](https://keras.io/) resource.

*****
