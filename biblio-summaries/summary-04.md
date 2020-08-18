# **Classification of Land Cover and Land Use Based on Convolutional Neural Networks** - Summary

- Land cover describes physical material; land use describes socio-economic function of land
- Each image pixel is assigned a class label indicating land cover (e.g. grass, asphalt)
- Land use objects can contain more than one land cover elements
- CNNs expanded to pixel-based classification of images (semantic segmentation)
- Irregularly shaped polygons is not as straight-forward since convolution layers of a CNN require a regular image grid
- This paper proposes the following methods:
    1. Extend the SegNet architecture to other input data than RGB images and propose a modified SegNet architecture having more layers while requiring fewer parameters
    2. Convert original input into a structure recognized by a CNN
    3. Compare different network variants and assess the contributions of individual data sources to the classification results
- Experiments have shown that an ensemble of CNN having different architectures and using different input data achieves the best results with an overall accuracy of almost 86% for eight land cover classes

