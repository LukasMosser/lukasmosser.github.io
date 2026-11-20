---
title: "Interpretation of deep neural networks for carbonate thin section classification"
collection: publications
permalink: /publication/2022-Interpretation-DNN-Carbonate-Thin-Sections
excerpt: 'This study uses ImageNet pretrained convolutional neural networks (CNNs), VGG11 and ResNet18 models to predict carbonate rock and pore types on a small dataset of 66 thin sections. We subsequently overlay Gradient Weighted Class Activation Maps (Grad-CAM) on top of the original thin section image to highlight features on which the neural network-based its decision-making, introducing an interpretability tool to the method.'
date: 2022-08-15
venue: 'Second International Meeting for Applied Geoscience & Energy (IMAGE)'
paperurl: 'https://doi.org/10.1190/image2022-3748082.1'
citation: 'Mosser, L., Ghon, G., & Baechle, G. (2022). Interpretation of deep neural networks for carbonate thin section classification. Second International Meeting for Applied Geoscience & Energy, 371-375.'
---
This study uses ImageNet pretrained convolutional neural networks (CNNs), VGG11 and ResNet18 models to predict carbonate rock and pore types on a small dataset of 66 thin sections. We subsequently overlay Gradient Weighted Class Activation Maps (Grad-CAM) on top of the original thin section image to highlight features on which the neural network-based its decision-making, introducing an interpretability tool to the method. Our findings show that pretrained CNNs can successfully learn feature representations in carbonate rock thin sections, achieving training F1 scores of over 90%. However, model generalization is a challenge on the small data set, and the risk of overfitting is investigated by freezing layers during training, achieving test F1 scores of over 65%. Interpretability with respect to rock and pore texture of these Grad-CAM heatmaps depends on the layer depth of the network: (a) High resolution shallower layers in both models show heatmap highlighted areas do correlate with rock textures (pores and grains) whereas (b) low spatial resolution deepest layers in VGG model show correlation between meaningful features in the heat maps provided by Grad-CAM and the actual rock texture in the full resolution image. Finally, neural networks trained on Dunham rock types show better interpretability than the pore type dataset.

[Read the paper here](https://doi.org/10.1190/image2022-3748082.1)
