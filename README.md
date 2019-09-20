# TomoGAN

https://arxiv.org/abs/1902.07582

An image quality enhancement model based on generative adversarial networks originally developed for synchrotron X-Ray tomography.

To give it a try:

* download sample dataset and the ImageNet pretrained vgg model from [Here](https://anl.box.com/s/h6koi0hhwqrj1c9tt82tldzo45tl3x15)

* install dependencies, Tensorflow(preferably 1.13)

* run with python ./main-gan.py -gpu 0 -expName test -xtrain dataset/noisy4train.h5 -ytrain dataset/clean4train.h5 -xtest dataset/noisy4test.h5 -ytest dataset/clean4test.h5


![Noisy Image](repo-image/ns-w016-i10-r25-s0364.png)
![Denoisied Image](repo-image/dn-w016-i10-r25-s0364.png)
