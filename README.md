# Cars Classification Kaggle Competition

### CS_T0828_HW1 Kaggle Competition:

You can download dataset from this Kaggle competition: https://www.kaggle.com/c/cs-t0828-2020-hw1/leaderboard

### Dataset Setup

After you download the dataset, put them in the root folder of your Google Drive.

The folder structures should like this:

datasets

----train_data

----val_data

----test_data

"..._data" folders should follow the structure of ImageFolder in Pytorch. (For test_data, you can just add dummy class.)

### Download Pretrained Model:

link: https://drive.google.com/file/d/1-ImdPz3gZahG7g7bo68oFI8T6EUJMnuF/view?usp=sharing

This model is trained on EfficientNet-b6 ("tf_efficientnet_b6_ns" in timm model)

### Inference

To inference, execute this(https://colab.research.google.com/drive/1ccnyNbx9Gr3gxHPcm1WEquTpDVZMB3cD?usp=sharing) Google Colab notebook from top to bottom. You can just skip the training session for inference.

#### Final Results

95.30% Accuracy

