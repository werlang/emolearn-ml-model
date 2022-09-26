# final

Fusion network:
* Fine-tuned InceptionResNetV3. TimeDistributed layer for training on videos. Also using ConvLSTM2D layers at the end of the network
* TCN network for training OpenFace features.
* Labels from previous time steps.

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

![image](https://user-images.githubusercontent.com/19828711/192367986-43ef4d35-0fb2-4541-8499-783380366ae1.png)

## Plot model

![image](final.png)
