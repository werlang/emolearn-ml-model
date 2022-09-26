# Emo-learn data

This repo reports most important data I gathered while doing my research on learning emotion recognition.

# Models overview

Here you find a short description of each model developed during my reaearch. You can also check more details on each model's folder.

| Models | Model Description | Metrics |
| --- | --- | --- |
| [vgg_fine_tune_v6](https://github.com/werlang/emolearn-ml-model/tree/main/vgg_fine_tune_v6) | VGG16 pre-trained on VGG-Face. GRU to get frames from videos. | 0.6362 acc, F1 0.6250 |
| [conv3d_v1](https://github.com/werlang/emolearn-ml-model/tree/main/conv3d_v1) | Conv3D sequential. | 0.7492 acc |
| [conv3d_v4](https://github.com/werlang/emolearn-ml-model/tree/main/conv3d_v4) | Conv3D with skip connections. | 0.7371 acc, F1 0.5025 |
| [time_v1](https://github.com/werlang/emolearn-ml-model/tree/main/time_v1) | BLSTM with skip connections for OpenFace features and TimeDistributed Conv2D with skip-connections for videos. Fusion with BLSTM. | 0.6733 acc |
| [daisee_eng_merge](https://github.com/werlang/emolearn-ml-model/tree/main/daisee_eng_merge) | Fine-tuned TimeDistributed InceptionResNetV3 + ConvLSTM2D for videos and TCN for OpenFace features. | 0.9417 acc, F1 0.5122 |
| [final](https://github.com/werlang/emolearn-ml-model/tree/main/final) | Same as *daisee_eng_merge* plus a network providing emotions from previous steps. | 0.XXXX acc |
| [personalities](https://github.com/werlang/emolearn-ml-model/tree/main/personalities) | aaa. | 0.XXXX acc |