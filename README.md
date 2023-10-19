# UNet-Semantic-Segmentation-Aerial-Imagery

In image segmentation, transfer learning helps deep learning models perform more accurately. This project focuses on the segmentation of satellite images and finding the best transfer learning technique with U-Net for precise image segmentation. 

🔹 Accuracy U-Net: 77%

🔹 Accuracy InceptionResNetV2: 87%

⚡ Dataset: https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery

⚡ The total volume of the dataset is 72 images grouped into 6 larger tiles => cut up images into 256x256 pieces to create a larger training set

⚡ The dataset consists of aerial imagery of Dubai obtained by MBRSC satellites and annotated with pixel-wise semantic segmentation in 6 classes: 

Building: #3C1098

Land (unpaved area): #8429F6

Road: #6EC1E4

Vegetation: #FEDD3A

Water: #E2A929

Unlabeled: #9B9B9B
