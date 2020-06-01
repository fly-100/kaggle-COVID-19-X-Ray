# Detecting COVID-19 from X-RAY Images using Deep Learning - 1st Place Kaggle Competition Winner

## Overview
- This [Kaggle competition](https://www.kaggle.com/c/4771-sp20-covid) was the final project of Columbia University's Machine Learning (COMS4705) course, taken by undergrads, grads, and PhDs, in spring 2020. 
- The task was to classify X-Ray images into one of four categories: COVID-19, bacterial pneumonia, viral pneumonia, and normal (meaning healthy).
- My solution [finished 1st place](https://www.kaggle.com/c/4771-sp20-covid/leaderboard) out of 180 participants in both the public and private leaderboard with weighted accuracy of 88.2% and 89.2%, respectively.
- Please see the [submitted writeup](https://github.com/shoyasaxa/kaggle-COVID-19-X-Ray/blob/master/sy2905_kaggle_writeup.pdf) for the details of my approach

## Approach 
- I finetuned 10 large CNNs such as DenseNet121 and ResNet101 and ensembled them together
