# Sample_NeuralStyleTransfer
This repository includes a sample of neural style transfer using deep learning with pytorch and the perceptual loss.

According to tensorflow.com: "Neural style transfer is an optimization technique used to take two images—a content image and a style reference image (such as an artwork by a famous painter)—and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image. This is implemented by optimizing the output image to match the content statistics of the content image and the style statistics of the style reference image. These statistics are extracted from the images using a convolutional network."

In this repo, I have implemented the neural style transfer with pure Pytorch and using the "perceptual loss" first introduced in this paper:
* https://arxiv.org/pdf/1603.08155.pdf

Also, I have endorsed some implementation techniques and tips from the following blog posts:
* https://towardsdatascience.com/neural-networks-intuitions-2-dot-product-gram-matrix-and-neural-style-transfer-5d39653e7916
* https://medium.com/@sashankpappu/style-transfer-using-pytorch-cb6225cf183e

You can open the notebook in this repo and try to play with the code by yourself!

Below is a sample of neural style transfer applied on one of my own images:
![](Sample_NST_img.png?raw=true "Title")
