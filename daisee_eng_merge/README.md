# daisee_eng_merge

Fusion network:
* Fine-tuned InceptionResNetV3. TimeDistributed layer for training on videos, also using ConvLSTM2D layers at the end of the network.
* TCN network for training OpenFace features.

## Notebook

[daisee_eng_merge.ipynb](https://github.com/werlang/emolearn-ml-model/blob/main/daisee_eng_merge/daisee_eng_merge.ipynb)

## Best weights

[2021-6-22-12-47-14-daisee-eng-merge/084.h5](https://drive.google.com/file/d/132GCUn-WV6TYFRFSwq1iqrYrrrPTVGlL/view?usp=sharing)

## Performance

| Accuracy |     F1 |
| -------: | -----: |
|   0.9417 | 0.5122 |

## Confusion Matrix

|       |    0 |    1 |
| ----- | ---: | ---: |
| **0** |    9 |  255 |
| **1** |   57 | 5028 |

## Loss and Accuracy during training

![image](https://user-images.githubusercontent.com/19828711/192119541-c62dcb8d-b2e1-4576-8b79-c3b735aba8e7.png)

## Plot model

![image](daisee_eng_merge.png)
