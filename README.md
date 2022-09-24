# Emo-learn data

This repo reports most important data I gathered while doing my research on learning emotion recognition.

# Models overview

Here you find a short description of each model developed during my reaearch. You can also check more details on each model's folder.

| Notebook | Best Weights | Model Description | Metrics |
| --- | --- | --- | --- |
| [vgg_fine_tune_v6.ipynb](https://github.com/werlang/emolearn-ml-model/blob/main/notebooks/vgg_fine_tune_v6.ipynb) | [2020-7-16-21-51-7-fine-tune-images-vgg-gru-striding-2/021.h5](https://drive.google.com/file/d/1-jdoX6Bf56LobF4xJqIezkO7ByTT8fwY/view?usp=sharing) |  VGG16 pre-trained on VGG-Face. GRU to get frames from videos. | 0.6362 acc, F1 0.6250 |
| [conv3d_v1.ipynb](https://github.com/werlang/emolearn-ml-model/blob/main/notebooks/conv3d_v1.ipynb) | [2020-8-25-18-33-42-conv3d-1st-try/004.h5](https://drive.google.com/file/d/1-7rH_p8JPH-VYcjXPhu_Axcs60I3NUIb/view?usp=sharing) | Conv3D sequential. | 0.7492 acc |
| [conv3d_v4.ipynb](https://github.com/werlang/emolearn-ml-model/blob/main/notebooks/conv3d_v4.ipynb) | [2020-10-21-14-23-53-conv3d-new-aligned-resnet/025.h5](https://drive.google.com/file/d/12fSbMV4Hiw98eCv3Z2DglPl9l-z4-32B/view?usp=sharing) | Conv3D with skip connections. | 0.7371 acc, F1 0.5025 |
| [time_v1.ipynb](https://github.com/werlang/emolearn-ml-model/blob/main/notebooks/time_v1.ipynb) | [2021-1-6-22-56-20-fusion-1e/022.h5](https://drive.google.com/file/d/10LdDkOL0RdoXESY5QC6kIj_ZbBaZTk6-/view?usp=sharing) | BLSTM with skip connections for OpenFace features and TimeDistributed Conv2D with skip-connections for videos. Fusion with BLSTM. | 0.6733 acc |
| [daisee_eng_merge.ipynb](https://github.com/werlang/emolearn-ml-model/blob/main/notebooks/daisee_eng_merge.ipynb) | [2021-6-22-12-47-14-daisee-eng-merge/084.h5](https://drive.google.com/file/d/132GCUn-WV6TYFRFSwq1iqrYrrrPTVGlL/view?usp=sharing) | Fine-tuned TimeDistributed InceptionResNetV3 for videos and TCN for OpenFace features. | 0.9417 acc, F1 0.5122 |
| [label_4e.ipynb](https://github.com/werlang/emolearn-ml-model/blob/main/notebooks/label_4e.ipynb) | | aaa. | 0.XXXX acc |
| [personalities.ipynb](https://github.com/werlang/emolearn-ml-model/blob/main/notebooks/personalities.ipynb) | | aaa. | 0.XXXX acc |

# Plot models

You can find a .png file with the image of each model is in the [model_image](https://github.com/werlang/emolearn-ml-model/tree/main/model_image) folder. The file is named after notebook's name.
