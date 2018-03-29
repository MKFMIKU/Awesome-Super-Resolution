# Awesome-Super-Resolution [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

⚡️ List of awesome super-resolution algorithms

- depth: Report in the paper that how many convolutional blocks the longest chain from the input to the output has passed 

- Loss function: Report in the paper that what loss function was used


| Name  | Depth(scale=2) | Loss function | Parameters |
| ---- | -- | ------ | --- |
| [SRCNN](https://arxiv.org/abs/1501.00092)  | 3 | MSE | `9*9*64*1 + 5*5*64*32 + 5*5*32*1=`57184 |
| [ESPCN](https://arxiv.org/abs/1609.05158)  | 3 | MSE | `5*5*64*1 + 3*3*64*32 + 3*3*32*4=`21184 |
| [FSRCNN](https://arxiv.org/abs/1608.00367)  | 8 | MSE | 22832 |
| [VDSR](https://arxiv.org/abs/1511.04587)  | 20 | MSE | 738432 |
| [DRCN](https://arxiv.org/abs/1511.04491)  | 20  | MSE | 1774080 |
| [DRRN](http://cvlab.cse.msu.edu/pdfs/Tai_Yang_Liu_CVPR2017.pdf) | 20 | MSE | 296064 |
| [SRGAN/SRResNet](https://arxiv.org/abs/1609.04802)  | 37 | perceptual loss | 1395072 |
| [LapSRN](https://arxiv.org/abs/1710.01992)  | 14 |  Charbonnier | 436624 |
| [EDSR](https://arxiv.org/abs/1707.02921)  | 67 | L1 | 3314816 |
