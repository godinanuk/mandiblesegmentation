# mandiblesegmentation
CycleGAN model for segmenting Mandibles from Panoramic Dental X-rays

|          Hyperparameter                      |        Value         |
|----------------------------------------------|----------------------|
| Number of epochs                             |          750         |
| Conv3D with sigmoid                          | 7,722,101            | 90 minutes     | 0.6023               | 0.8920                   |
| Conv2D + GRU with sigmoid                    | 5,304,869            | 64 minutes     | 0.2933               | 0.8760                   |
| Conv2D + LSTM with sigmoid                   | 5,500,965            | 52 minutes     | 0.3127               | 0.8720                   |
| Conv2D + GRU + VGG16 with sigmoid            |   306,965            | 113 minutes    | 0.3336               | 0.8540                   |
| Conv2D + GRU + InceptionV3 with sigmoid      |   536,341            | 92 minutes     | 0.4195               | 0.8420                   |
| Conv2D + GRU + Resnet50 with sigmoid         | 2,109,205            | 69 minutes     | 0.4973               | 0.8000                   |
| Conv2D + GRU + Xception with sigmoid         | 2,109,205            | 91 minutes     | 0.4526               | 0.8080                   |
| Conv2D + GRU + MobileNetV2 with sigmoid      | 1,322,773            | 69 minutes     | 0.4925               | 0.7120                   |
| Conv2D + GRU + EfficientNetB7 with sigmoid   | 2,633,493            | 81 minutes     | 0.6262               | 0.7200                   |

| Number of epochs                                              | 750  |
------------------------------------------------------------------------
| Optimizer                                                     | Adam |
------------------------------------------------------------------------
| Activation function used in final layer of Generator function | tanh |

