# mandiblesegmentation
CycleGAN model for segmenting Mandibles from Panoramic Dental X-rays

|          Hyperparameter                                           |        Value         |
|-------------------------------------------------------------------|----------------------|
| Number of epochs                                                  |          750         |
| Optimizer                                                         |         Adam         | 
| Activation function used in final layer of Generator function     |         tanh         |              

**Best training SSIM metric achieved is 0.6715**

**Best training DSC  metric achieved is 0.9846**


<p align="center"><img width="80%" src="loss_chart.png" /></p>
<p align="center"><b>Plot of Generator Loss vs Discriminator Loss</b></p>

<p align="center"><img width="80%" src="test_results.png" /></p>
<p align="center"><b>Test results</b></p>
