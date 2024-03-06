# Multiclass Semantic Segmentation on Aerial Imagery Using CNN-based and Transformers-based U-Net Models

Transfer learning significantly enhances the accuracy of deep learning models in image segmentation. This project focuses on the utilization of a CNN architecture (U-Net) and finding the best transfer learning technique for precise satellite image segmentation, which plays an important role in various applications such as urban planning, environmental monitoring, and disaster management Accomplish this, three different transfer learning approaches were employed: pre-trained VGG19, InceptionResNetV2, and DenseNet-121 models. The visual results and dice coefficients of these models were compared. Notably, the "DenseNet-121" model achieved an accuracy of 89% and a loss of 0.3327. By comparing transfer learning models, this project aims to increase the accuracy of multiclass semantic segmentation on satellite images. This project is implemented in TensorFlow 

⚡ Dataset: https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery

⚡ The total volume of the dataset is 72 images grouped into 6 larger tiles => cut up images into 256x256 pieces to create a larger training set

⚡ The dataset consists of aerial imagery of Dubai obtained by MBRSC satellites and annotated with pixel-wise semantic segmentation in 6 classes: 
