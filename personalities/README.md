# personalities

<!-- Fusion network:
* Fine-tuned InceptionResNetV3. TimeDistributed layer for training on videos.
* TCN network for training OpenFace features.
* Labels from previous time steps.

Before concatenating both networks, using ConvLSTM2D layers at the end of the video network. -->

## Notebook

[personalities.ipynb](https://github.com/werlang/emolearn-ml-model/blob/main/personalities/personalities.ipynb)

## Best weights

[2021-12-8-20-41-45-personality/102.h5](https://drive.google.com/file/d/12UZ8sVycG3bLdVZw5jfRc38B3nJStWEW/view?usp=sharing)

## Performance

| Accuracy | F1 |
| --- | --- |
| 0.9018 | 0.8870 |

## Confusion Matrix

<!-- | | 0 | 1 |
| --- | --- | --- |
| **0** | 264 | 322 | 
| **1** | 553 | 4858 | -->

## Loss and Accuracy during training

<!-- ![image](https://user-images.githubusercontent.com/19828711/192119541-c62dcb8d-b2e1-4576-8b79-c3b735aba8e7.png) -->

## Plot model

![image](personalities.png)
