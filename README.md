# SKT-FLY-AI-Computer-vision-and-Front-end-Study
Computer Vision and Front-end Study Group held at SKT FLY AI

# 2023 LG DISPLAY Quality Classification 1st place Solution
AI solution that Classifies the Product Quality

## Team member
|<img src="https://avatars.githubusercontent.com/jeongiin" width="100">| <img src="https://avatars.githubusercontent.com/" width="100">|<img src="https://avatars.githubusercontent.com/YUL-git" width="100">||<img src="https://avatars.githubusercontent.com/yunhee1" width="100">
|-|-|-|-|
Leader|[Jeongin Lee](https://github.com/jeongiin), |[Hanik Cho](https://github.com/), |[Jiyul Ham](https://github.com/YUL-git), |[Yoonhee Hwang](https://github.com/yunhee1)  

## File Structure
```
┖ Jeongin Lee
  ┖ ~
┖ Hanik Cho
  ┖ ~
┖ Jiyul Han
  ┖ ~
┖ Yoonhee Hwang
  ┖ ~
```

del_feature.ipynb
- Feature Selection using SHAP value for train fitted classification model

numpy_selected_feature_5fold_original_300.npy
- numpy array that contains the information of Selected Feature from `del_feature.ipynb`

sub_with_reg_and_cls_422.ipynb
- Train and Test the classification and regression model

## Dataset
We train and evaluate our model using the dataset from [Classifying Smart Factory Product Quality Status](https://dacon.io/en/competitions/official/236080/data)

we assume that you have downloaded it and placed based on File Structure, inside the dataset folder.

## Submission Process
1. Run All code in `del_feature.ipynb` to select important features and save in the `numpy_selected_feature_5fold_original_300.npy` file.

2. Run All code in `sub_with_reg_and_cls_422` to classify product quality using the regression model and classification model.
