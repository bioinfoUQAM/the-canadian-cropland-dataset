---
layout: default
title: Benchmarking
nav_order: 4
---

# Benchmarking
{: .no_toc }

<br>
<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>
<br>

We present two classification experiments performed using the 2019 version of the dataset to infer the main crop types present in each image. In the first experiment, *static classification*, we treated each individual image as a training instance (static image classification). In the second experiment, *dynamic classification* we explored the use of a temporal image series as an input. 

<p align="center"><img src="figures/benchmarking/classification_experiments.png" alt="Classification Experiment" width="1000"></p>
 
## Results

### Static Classification  

The deep learning models used for the static classification task include the [*ResNet-50*](https://arxiv.org/abs/1512.03385), the [*DenseNet*](https://arxiv.org/abs/1608.06993) and the [*EfficientNet-B0*](https://arxiv.org/abs/1905.11946).   

<table style="border-collapse: collapse; table-layout: fixed; width: 100%;">
  <tr>
    <th style="border: 1px solid black; text-align: center;">Models/Metrics</th>
    <th style="border: 1px solid black; text-align: center;">Precision</th>
    <th style="border: 1px solid black; text-align: center;">Recall</th>
    <th style="border: 1px solid black; text-align: center;">F1-Score</th>
    <th style="border: 1px solid black; text-align: center;">Accuracy</th>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">DENSENET-121 (RGB)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
<tr>
    <td style="border: 1px solid black; text-align: center;">DENSENET-121 (GNDVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">DENSENET-121 (NDVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">DENSENET-121 (NDVI45)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">DENSENET-121 (OSAVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">DENSENET-121 (PSRI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">EFFN-B0 (RGB)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">EFFN-B0 (GNDVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">EFFN-B0 (NDVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">EFFN-B0 (NDVI45)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">EFFN-B0 (OSAVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">DEFFN-B0 (PSRI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">RES-SCR (RGB)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">RES-SCR (PSRI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">RES-SCR (NDVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">RES (RGB)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">RES (GNDVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">RES (NDVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">RES (NDVI45)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">RES (OSAVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">RES (PSRI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr> 
  </table>  
<br>

### Dynamic Classification

The deep learning models used for the dynamic classification task include the [*3 Dimensional Convolutional Network (3DCNN)*](https://arxiv.org/abs/2007.13224) and the [*Long-Term Recurrent Convolutional Networks (LRCN)*](https://arxiv.org/abs/1411.4389). 


<table style="border-collapse: collapse; table-layout: fixed; width: 100%;">
  <tr>
    <th style="border: 1px solid black; text-align: center;">Models/Metrics</th>
    <th style="border: 1px solid black; text-align: center;">Precision</th>
    <th style="border: 1px solid black; text-align: center;">Recall</th>
    <th style="border: 1px solid black; text-align: center;">F1-Score</th>
    <th style="border: 1px solid black; text-align: center;">Accuracy</th>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">LRCN-64 (RGB)</td>
    <td style="border: 1px solid black; text-align: center;">0.610 ± 0.017</td>
    <td style="border: 1px solid black; text-align: center;">0.637 ± 0.015</td>
    <td style="border: 1px solid black; text-align: center;">0.617 ± 0.013</td>
    <td style="border: 1px solid black; text-align: center;"><strong>0.774 ± 0.014</strong></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">LRCN-64 (GNDVI)</td>
    <td style="border: 1px solid black; text-align: center;">0.030 ± 0.000</td>
    <td style="border: 1px solid black; text-align: center;">0.100 ± 0.000</td>
    <td style="border: 1px solid black; text-align: center;">0.040 ± 0.000</td>
    <td style="border: 1px solid black; text-align: center;">0.277 ± 0.006</td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">LRCN-64 (NDVI)</td>
    <td style="border: 1px solid black; text-align: center;">0.030 ± 0.000</td>
    <td style="border: 1px solid black; text-align: center;">0.100 ± 0.000</td>
    <td style="border: 1px solid black; text-align: center;">0.040 ± 0.000</td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">LRCN-64 (NDVI45)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">LRCN-64 (OSAVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">LRCN-64 (PSRI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">3D-CNN (RGB)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">3D-CNN (GNDVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">3D-CNN (NDVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">3D-CNN (NDVI45)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">3D-CNN (OSAVI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border: 1px solid black; text-align: center;">3D-CNN (PSRI)</td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
    <td style="border: 1px solid black; text-align: center;"></td>
  </tr>
</table>  
<br>

The LRCN and 3D-CNN architectures showed higher average accuracies (0.77 for both models). Our overall results showed that classifiers trained with the triplets outperformed the static models (10% increase in accuracy, 0.773 vs 0.667, p<0.05).
Furthermore, more complex models (≥ 5.38 millions of parameters) underperformed in contrast to the 3D-CNN (around 31,000 parameters).


<div align="center">
  <img src="figures/benchmarking/results_all_models_no_ResScr.png" width="1000" >
</div>


## Use Cases
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

______