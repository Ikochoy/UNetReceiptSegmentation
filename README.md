# UNet Experiment On Receipt Image Segmentation

This project serves as a feasbility study on how a UNet model would perform with our dataset. Unlike traditional use case, due to the special conditions of our POC, the background of 
the receipts would not be a plane or a one-color desk. Hence, we can't use traditional image processing techniques like canny edge, laplacian edge detection in combination of  `cv2.findContours` 
to find the contours of the receipt. 

UNet Implementation Guide References: 
- https://arxiv.org/pdf/1505.04597
- https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/image_segmentation/semantic_segmentation_unet
