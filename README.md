# colon_polyps_unet

Public Dataset taken from: 

[Polyp - Grand Challenge](https://polyp.grand-challenge.org/Databases/)

* Training data\* consists of [CVC-ClinicDB dataset](https://polyp.grand-challenge.org/CVCClinicDB/)
* Test data consists of the [ETIS-Larib dataset](https://polyp.grand-challenge.org/EtisLarib/)


\* a private data set was also used for training provided by a UCI professor and graduate student to help with training


Model: UNet

* Original Paper: [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)

* Model was run on 25 epochs with some image preprocessing for the normal image preprocessing reasons as well as to expand the number of images for training

* Results may vary slightly if model is run as is since my model uses a private dataset that I am not allowed to provide here
