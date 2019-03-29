Tensorflow-MNIST-cWDCGAN
===

## 使用cWDCGAN生成近乎完美的MNIST手写数字/Generate near-perfect MNIST handwritten numbers using cWDCGAN

<br><br>
本项目中使用的神经网络被叫做cWDCGAN，它是cGAN、WGAN、DCGAN的一种结合。它的训练速度快、生成图像多样性高，具有十分优良的性能。<br>
<br>
如果代码文件在Github上无法直接查看，可以点击[这里](https://nbviewer.jupyter.org/github/XiaTianXing/Tensorflow-MNIST-cWDCGAN/blob/master/MNIST-cWDCGAN.ipynb)查看。<br><br><br>

## 生成图像可视化<br>
在神经网络训练过程中，每训练40步就保存一次测试图像。图像的期望数值为1-8升序，输入噪声全部固定成0.5，将其合成为动图:<br>
![](https://github.com/XiaTianXing/Tensorflow-MNIST-cWDCGAN/blob/master/picture/20190306_162713.gif)<br>
<br>
在训练结束后通过调节噪声插值生成手写数字图像，并合成为动图：<br>
![](https://github.com/XiaTianXing/Tensorflow-MNIST-cWDCGAN/blob/master/picture/20190306_162913.gif)

