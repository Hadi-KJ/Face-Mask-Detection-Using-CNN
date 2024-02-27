# Face-Mask-Detection-Using-CNN

Dataset: https://www.kaggle.com/datasets/omkargurav/face-mask-dataset

Dataset split folders: train - dev - test

![Screen Shot 1402-12-07 at 16 26 05](https://github.com/HKJ91/Face-Mask-Detection-Using-CNN/assets/74920157/b5bbca23-4705-4a12-a3f4-12175fad717a)

Accuracy without transfer learning: 89.6%

Accuracy with transfer learning on MobileNet model: 99.1%

# Downlaoding dataset using kaggle:

!pip install kaggle
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json
!kaggle datasets download -d omkargurav/face-mask-dataset
!unzip "/content/face-mask-dataset.zip"
