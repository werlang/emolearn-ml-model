# conv3d_v4

Conv3D network created using skip connections. Inspired on how ResNet works.

## Notebook

[conv3d_v4.ipynb](https://github.com/werlang/emolearn-ml-model/blob/main/conv3d_v4/conv3d_v4.ipynb)

## Best weights

[2020-10-21-14-23-53-conv3d-new-aligned-resnet/025.h5](https://drive.google.com/file/d/12fSbMV4Hiw98eCv3Z2DglPl9l-z4-32B/view?usp=sharing)

## Performance

| Accuracy | F1 |
| --- | --- |
| 0.7371 | 0.5025 |

## Confusion Matrix

| | 0 | 1 |
| --- | --- | --- |
| **0** | 45 | 43 | 
| **1** | 426 | 1270 |

## Plot model

![image](conv3d_v4.png)
