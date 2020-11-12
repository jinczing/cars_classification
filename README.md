# Cars Classification Kaggle Competition

### CS_T0828_HW1 Kaggle Competition:

You can download dataset from this Kaggle competition: https://www.kaggle.com/c/cs-t0828-2020-hw1/leaderboard

### Dataset Setup

After you download the dataset, put them in the root folder of your Google Drive.

The folder structures should like this:

datasets

----car classification

--------train_data

------------class 1

----------------image 1

----------------...

--------val_data

------------class 1

----------------image 1

----------------...

--------test_data

------------dummy

----------------image 1

### Download Pretrained Model:

link: https://drive.google.com/file/d/1-ImdPz3gZahG7g7bo68oFI8T6EUJMnuF/view?usp=sharing

This model is trained on EfficientNet-b6 ("tf_efficientnet_b6_ns" in timm model)

### Inference

To inference, execute the cars_classification.ipynb from top to bottom(I recommend running on Google Colab). You can just skip the training session for inference.

#### Final Results

95.30% Accuracy

