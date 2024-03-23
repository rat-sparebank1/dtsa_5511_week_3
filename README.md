## Introduction
The goal for this notebook is to produce a submission file to participate in Kaggle Histopathologic Cancer Detection. https://www.kaggle.com/competitions/histopathologic-cancer-detection

## Dataset description:
The dataset consists on 277485 files divided into train and test files. The files are: one csv file with label information for the training set and tif files with pictures of healthy and cancerous tissue. All images are classified. It seems that there is no need for extensive EDA

## Problem description:
Classify the pictures on the test folder using the training data provided in the train folder and the labels store in the csv file. The image must be classified as 1 (cancerous) if the center 32x32 pixel region contains at least one pixel of tumor tissue.

## Approach:
This notebook is designed to be run in Colab: https://colab.research.google.com/drive/1UmctxlnzMS3buPK4hUQXxeQ3bMJVVNO9#scrollTo=G0Ki24SayXSq
