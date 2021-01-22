# Pneumonia detection

I've always been very keen into life-sciences and healthcare, so when I decided to become a Data Scientist and discovered how powerful and useful Machine and Deep Learning could be, I started to think on creating something to help others. 

This project is the result of pursuing that goal: I've created a high accuracy model using Machine Learning and neural networks to diagnose pneumonia reading chest X-ray images.

`Neural networks (CNN)` | `tensorflow` | `keras` | `93% accuracy` | `0.98 recall`



## Overview

- `images`: folder contains representative images from this project.
- `models`: folder contains the json file with the final model.history details and the url to get the trained model.
- `presentation`: folder contains the file used for presenting this project.
- `X-ray code.ipynb`: contains all the code.

## Data details

Data downloaded from [kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/metadata).

- 5,863 images.
- 2 categories: PNEUMONIA, NORMAL.

The final model was trained in kaggle notebooks using GPU.
