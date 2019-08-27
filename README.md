# Modified Pix2Pix

Reimplementation the Pix2Pix model for a small dataset with less parameters and different Patch-Net architecture

Google Code[Tensoflow]: https://github.com/tensorflow/docs/blob/r2.0rc/site/en/r2/tutorials/generative/pix2pix.ipynb


U-Net:

<img align="center" src="unet.png">

Patch-Net:

<img align="center" src="patchnet.png">



Pix2Pix:

<img align="center" src="pix2pix.png">


# Result

It is trained on the Cifar10 dataset to reconstruct every input image(auto-encoding) and it has 0.006 MAE on the test set.
