# daisee_eng_merge

Fusion network:
* Fine-tuned InceptionResNetV3. TimeDistributed layer for training on videos.
* TCN network for training OpenFace features.

Before concatenating both networks, using ConvLSTM2D layers at the end of the video network.

## Notebook

[daisee_eng_merge.ipynb](https://github.com/werlang/emolearn-ml-model/blob/main/daisee_eng_merge/daisee_eng_merge.ipynb)

## Best weights

[2021-6-22-12-47-14-daisee-eng-merge/084.h5](https://drive.google.com/file/d/132GCUn-WV6TYFRFSwq1iqrYrrrPTVGlL/view?usp=sharing)

## Performance

| Accuracy | F1 |
| --- | --- |
| 0.9417 | 0.5122 |

## Plot model

![image](daisee_eng_merge.png)
