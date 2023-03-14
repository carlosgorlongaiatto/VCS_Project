# Multi-scale patch-wise semantic segmentation of satellite images using U-Net architecture

## Authors:
- [Eugenio Fella](https://github.com/eugeniofella)
- [Theivan Pasupathipillai](https://github.com/TheivanPasu)
- [Carlo Sgorlon Gaiatto](https://github.com/carlosgorlongaiatto)

## Abstract:
This paper presents a semantic segmentation technique for satellite images using deep convolutional neural networks. We utilize the DeepGlobe Land Cover Classification dataset and employ a patch-wise pre-processing pipeline, including image rescaling and data augmentation, to improve the representation of input image features and cope with computational challenges. The imbalance between classes is addressed by weighting the multi-class cross entropy loss function. We implement a U-Net architecture as the baseline and demonstrate improvements with our approach. We also compare it with the state-of-the-art model, DeepLabV3+, fine-tuned on the dataset. The results indicate that our method achieves competitive performance according to the chosen metrics, showing its effectiveness in accurately segmenting satellite images. It outperforms the DeepGlobe challenge baseline score and it is comparable to the competition winners.

![Alt Text](/resources/images/U_Net_prediction_with_patches.jpeg)
