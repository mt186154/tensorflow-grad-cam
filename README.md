

# Grad-Cam - Tensorflow Slim 

<img src="https://github.com/hiveml/tensorflow-grad-cam/blob/master/images/cat_heatmap.png">

<img src="https://github.com/hiveml/tensorflow-grad-cam/blob/master/images/scarjo.png">

### Features:

Modular with Tensorflow slim. Easy to drop in other [Slim Models](https://github.com/tensorflow/models/tree/master/research/slim#pre-trained-models)

Udated to work with Tensorflow 1.5

Includes various output options: heatmap, shading, blur

#### Link to blog post


### Dependencies

* `pip install tensorflow`
* `pip install scikit-image`
* `sudo apt-get install python-tk`
* Opencv - see https://docs.opencv.org/2.4/doc/tutorials/introduction/linux_install/linux_install.html

### Installation

Clone the repo:
```
git clone https://github.com/hiveml/tensorflow-grad-cam.git
cd tensorflow-grad-cam
```
Download the ResNet-50 weights:
```
./imagenet/get_checkpoint.sh
```
### Usage
```
./main.sh
```

### Changing the Class

Show gambling example

### How to load another resnet model

### How to load another architecture
