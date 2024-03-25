# Multiclass Semantic Segmentation on Aerial Imagery Using U-Net and UNETR (Vision Transformers U-Net)

⚡ A Comparison of CNN-based U-Net (Attention Unet, CNN Unet, VGG19 Unet, Densenet-121 Unet),  and UNETR (Vision Transformers-based U-Net) Models for Multiclass Semantic Segmentation on Aerial Images

The UNETR architecture utilizes a Transformer as the encoder to learn sequence representations of input images and effectively capture the global multi-scale information, following this, there is a CNN-based decoder to upsample the global representations and generate the final segmentation mask.

[UNETR: Transformers for 3D Medical Image Segmentation],
Ali Hatamizadeh, Dong Yang, Holger Roth, Daguang Xu. 2021. (https://arxiv.org/abs/2103.10504?context=cs.CV)

<img width="741" alt="19c387ec-df70-4d60-847f-331910aa384f" src="https://github.com/NiloofarAZAD/ViT-and-CNN-Based-UNet-Models-Semantic-Segmentation-Aerial-Imagery/assets/128168974/ea6af991-460c-4c84-a2f6-e0c15f99c99c">


⚡ Dataset: https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery

The dataset consists of aerial imagery of Dubai obtained by MBRSC satellites and annotated with pixel-wise semantic segmentation in 6 classes.The total volume of the dataset is 72 images grouped into 6 larger tiles => cut up images into 256x256 pieces to create a larger training set. 
