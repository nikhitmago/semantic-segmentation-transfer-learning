# Semantic Segmentation using Fully Convolutional Networks (FCN - 32/16)


- I have implemented two FCNs (FCN-32 and FCN-16) to semantically segment images using the VOCSegmentation2012 dataset. 
- Semantic segmentation is a bit different from classification, where we classify each pixel as a particular class. 
- I've used Transfer Learning by transfering initial weigths of VGG-16 network and replacing classification layer with convolution layers.
- mean IOU and DICE score are the evaluation metrics.
