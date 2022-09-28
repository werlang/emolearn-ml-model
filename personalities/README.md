# personalities

Fusion network:
* Fine-tuned InceptionResNetV3. TimeDistributed layer for training on videos. Also using ConvLSTM2D layers at the end of the network
* TCN network for training OpenFace features.
* Labels from previous time steps.
* Personalities of the subject.

## Notebook

[personalities.ipynb](https://github.com/werlang/emolearn-ml-model/blob/main/personalities/personalities.ipynb)

## Best weights

[2021-12-8-20-41-45-personality/102.h5](https://drive.google.com/file/d/12UZ8sVycG3bLdVZw5jfRc38B3nJStWEW/view?usp=sharing)

## Performance

| Accuracy |     F1 |
| -------: | -----: |
|   0.9018 | 0.8870 |

## Confusion Matrix

|       |    0 |    1 |
| ----- | ---: | ---: |
| **0** |  206 |   17 |
| **1** |   15 |   88 |

## Loss and Accuracy during training

![image](https://user-images.githubusercontent.com/19828711/192368965-d6838870-7d2b-4a92-9a41-7d0c2f636c3b.png)

## Plot model

![image](personalities.png)
