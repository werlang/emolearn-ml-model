# final

<!-- Fusion network:
* Fine-tuned InceptionResNetV3. TimeDistributed layer for training on videos.
* TCN network for training OpenFace features.
* Labels from previous time steps.

Before concatenating both networks, using ConvLSTM2D layers at the end of the video network. -->

## Notebook

[final.ipynb](https://github.com/werlang/emolearn-ml-model/blob/main/final/final.ipynb)

## Best weights

[2022-8-8-17-18-19-final/062.h5](https://drive.google.com/file/d/10Qat8h1GQ3F_uOmYJd9zXuQCHICLCNAc/view?usp=sharing)

## Performance

| Accuracy | F1 |
| --- | --- |
| 0.8541 | 0.6468 |

## Confusion Matrix

| | 0 | 1 |
| --- | --- | --- |
| **0** | 264 | 322 | 
| **1** | 553 | 4858 |

## Loss and Accuracy during training

<!-- ![image](https://user-images.githubusercontent.com/19828711/192119541-c62dcb8d-b2e1-4576-8b79-c3b735aba8e7.png) -->

## Plot model

![image](final.png)
