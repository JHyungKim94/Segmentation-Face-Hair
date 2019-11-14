## Segmentation

### 1. Network: Unet based on VGG16
: face_seg.ipynb is constructed on Unet based on VGG16. Because Unet has advantage of Symmetric, better resolution than FCN(Fully Convolutional Network).

### 2. Dataset: LFW
: images 13,233(1680 people with two or more images, + masks 2,927)
> http://vis-www.cs.umass.edu/lfw/

### 3. Future plan(Further More)
a. Why symmetric?: FCN is learning on only single scale…

b. In DCNN: Apply Dilated Convolution → ASPP(Atrous Spatial Pyramid Pooling)

c. In Post processing: Apply Fully connencted CRF(Conditional Random Field)

> b~c: in Deeplab v2 paper, contribution 

### 4. Reference
a. "Fully Convolutional Networks for Semantic Segmentation" (Jonathan Long, Evan Shelhamer, Trevor Darrell)

b. "Learning Deconvolution Network for Semantic Segmentation" (Hyeonwoo Noh, Seunghoon Hong, Bohyung Han)

c. "U-Net: Convolutional Networks for Biomedical Image Segmentation" (Olaf Ronneberger, Philipp Fischer, Thomas Brox)
