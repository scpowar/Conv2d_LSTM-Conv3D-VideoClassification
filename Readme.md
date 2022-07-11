# Hand Gesture Recognition
 Hand Gesture Recognition using CNN+LSTM/3D CNN

## Experiments Performed

### CNN+LSTM

1. **four layers of Conv2d + one layer of LSTM**

   | Dataset      | Classes | Samples | Best Test Acc | Best Test Loss |
   | ------------ | ------- | ------- | ------------- | -------------- |
   | CSL_Isolated | 100     | 25,000  | 82.08%        | 0.734426       |
   | CSL_Isolated | 500     | 125,000 | 71.71%        | 1.332122       |

2. **four layers of Conv2d + one layer of LSTM** - adding droput layer

   | Dataset      | Classes | Samples | Best Test Acc | Best Test Loss |
   | ------------ | ------- | ------- | ------------- | -------------- |
   | CSL_Isolated | 100     | 25,000  | 93.54%        | 0.245582       |
   | CSL_Isolated | 500     | 125,000 | 83.17%        | 0.748759       |

### 3D CNN

1. **three layers of Conv3d**

   | Dataset      | Classes | Samples | Best Test Acc | Best Test Loss |
   | ------------ | ------- | ------- | ------------- | -------------- |
   | CSL_Isolated | 100     | 25,000  | 58.86%        | 1.560049       |
   | CSL_Isolated | 500     | 125,000 | 45.07%        | 2.255563       |
   
2. **3D ResNet**

   | Method    | Dataset      | Classes | Samples | Best Test Acc | Best Test Loss |
   | --------- | ------------ | ------- | ------- | ------------- | -------------- |
   | ResNet18  | CSL_Isolated | 100     | 25,000  | 93.30%        | 0.246169       |
   | ResNet18  | CSL_Isolated | 500     | 125,000 | 79.42%        | 0.800490       |
   | ResNet34  | CSL_Isolated | 100     | 25,000  | 94.78%        | 0.207592       |
   | ResNet34  | CSL_Isolated | 500     | 125,000 | 81.61%        | 0.750424       |
   | ResNet50  | CSL_Isolated | 100     | 25,000  | 94.36%        | 0.232631       |
   | ResNet50  | CSL_Isolated | 500     | 125,000 | 83.15%        | 0.803212       |
   | ResNet101 | CSL_Isolated | 100     | 25,000  | 95.26%        | 0.205430       |
   | ResNet101 | CSL_Isolated | 500     | 125,000 | 83.18%        | 0.751727       |


## References

- [Can Spatiotemporal 3D CNNs Retrace the History of 2D CNNs and ImageNet?](https://arxiv.org/pdf/1711.09577.pdf)

- [Spatial Temporal Graph Convolutional Networks for Skeleton-Based Action Recognition](https://arxiv.org/pdf/1801.07455.pdf)
- [A Closer Look at Spatiotemporal Convolutions for Action Recognition](https://arxiv.org/abs/1711.11248)
- [SIGN LANGUAGE RECOGNITION WITH LONG SHORT-TERM MEMORY](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7532884)
- https://github.com/HHTseng/video-classification
- https://github.com/kenshohara/3D-ResNets-PyTorch

- https://github.com/bentrevett/pytorch-seq2seq
