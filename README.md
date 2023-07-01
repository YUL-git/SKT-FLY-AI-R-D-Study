# SKT-FLY-AI-Computer-vision-and-Front-end-Study
Computer Vision and Front-end Study Group held at SKT FLY AI

## Team member
<table>
  <tr>
    <td align="center"><a href="https://github.com/jeongiin"><img src="https://avatars.githubusercontent.com/u/48753785?v=4" width="200px;" alt="teammember1"/><br /><h3><b><a href="https://github.com/jeongiin">Jeongin Lee</b></h3></a><br /></td>
    <td align="center"><a href="https://github.com/"><img
src="" width="200px;" alt="teammember2"/><br /><h3><b><a href="https://github.com/">Hanik Cho</b></h3></a><br /></td>
    <td align="center"><a href="https://github.com/YUL-git"><img src="https://avatars.githubusercontent.com/u/89930713?v=4" width="200px;" alt="teammember2"/><br /><h3><b><a href="https://github.com/YUL-git">Jiyul Ham</b></h3></a><br /></td>
    <td align="center"><a href="https://github.com/YUL-git"><img src="https://avatars.githubusercontent.com/u/100117015?v=4" width="200px;" alt="teammember2"/><br /><h3><b><a href="https://github.com/yunhee1">Yoonhee Hwang</b></h3></a><br /></td>
  </tr>
<table>
  
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
