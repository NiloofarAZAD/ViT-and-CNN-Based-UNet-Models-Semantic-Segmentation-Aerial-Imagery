# Multiclass Semantic Segmentation on Aerial Imagery Using U-Net and UNETR (Vision Transformers U-Net)

⚡ In this project, I built a couple of UNet-based models for the task of Multiclass Semantic Segmentation of aerial images of Dubai to compare their performance.

I built 5 models including the classic UNet and Vision-Transformer-based UNet (UNETR).
The other 3 models are variations of it (VGG19-UNet, Densenet-121-UNet, Attention-UNet)

⚡ In conclusion, using 2088 images to train models, Densenet-121-Unet achieved the best performance with an accuracy of 89% compared to others. The UNETR model achieves around 72.09% accuracy on the test data. However, this is not a competitive result on a rather small dataset compared to CNNs on the same data. CNNs achieve excellent results on data volumes that are not as large as those required by Vision Transformers.

⚡ Dataset: https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery

The dataset consists of aerial imagery of Dubai obtained by MBRSC satellites and annotated with pixel-wise semantic segmentation in 6 classes. The total volume of the dataset is 72 images grouped into 6 larger tiles => cut up images into 256x256 pieces and use data augmentation to create a larger training set. 

------------------------------------------------------------------------
UNETR:

The UNETR architecture utilizes a Transformer as the encoder to learn sequence representations of input images and effectively capture the global multi-scale information, following this, there is a CNN-based decoder to upsample the global representations and generate the final segmentation mask.

[UNETR: Transformers for 3D Medical Image Segmentation],
Ali Hatamizadeh, Dong Yang, Holger Roth, Daguang Xu. 2021. (https://arxiv.org/abs/2103.10504?context=cs.CV)

<img width="741" alt="UNETR_img" src="https://github.com/NiloofarAZAD/ViT-and-CNN-Based-UNet-Models-Semantic-Segmentation-Aerial-Imagery/assets/128168974/15bb4851-be16-45cb-826a-fb1023bc5a5d">
