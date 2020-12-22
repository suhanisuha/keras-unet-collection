# keras-unet-collection

This repository contains `tensorflow.keras` implementations of U-net and its variants. Details of these models are listed as follows:

* [U-net] Ronneberger, O., Fischer, P. and Brox, T., 2015, October. U-net: Convolutional networks for biomedical image segmentation. In International Conference on Medical image computing and computer-assisted intervention (pp. 234-241). Springer, Cham.

* [U-net++] Zhou, Z., Siddiquee, M.M.R., Tajbakhsh, N. and Liang, J., 2018. Unet++: A nested u-net architecture for medical image segmentation. In Deep Learning in Medical Image Analysis and Multimodal Learning for Clinical Decision Support (pp. 3-11). Springer, Cham.

* [Attention U-net] Oktay, O., Schlemper, J., Folgoc, L.L., Lee, M., Heinrich, M., Misawa, K., Mori, K., McDonagh, S., Hammerla, N.Y., Kainz, B. and Glocker, B., 2018. Attention u-net: Learning where to look for the pancreas. arXiv preprint arXiv:1804.03999.

# Dependencies

* TensorFlow 2.3.0

* Keras 2.4.0

# Usage

Juptyer notebooks are provided as [user guides](https://github.com/yingkaisha/keras-unet-collection/blob/main/user_guid.ipynb).

# Overview

U-net is a convolutional neural network with encoder-decoder architecture and skip-connections, loosely defined under the concept of “fully convolutional networks." U-net was originally proposed for the semantic segmentation of medical images and is modified for solving a wider range of gridded learning problems.

U-net and many of its variants take three-dimensional tensors as inputs and produce outputs of the same shape. One technical highlight of these models is the skip-connections from downsampling to upsampling layers, which benefits the reconstruction of high-resolution, gridded outputs.

# Contact

Yingkai (Kyle) Sha <yingkai@eoas.ubc.ca>
