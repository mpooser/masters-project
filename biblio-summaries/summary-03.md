# **Labeling Land**: Land Use Classification Using Convolutional Neural Networks - Summary

- Dataset: EuroSAT Sentinel-2 satellite images from the German Research Center for AI
- Consists of 27,000 labeled images of 10 different land use classes
- Each image consists of 13 different color bands
- During translating, author used R, G, and B bands
- Used a CNN for first model:
    - one convolutional input layer
    - one flatten layer in the middle
    - one dense output later using ADAM optimizer
    - Accuracy of around 11% for five epochs
- Use Transfer Learning to improve the performance of this model on the dataset
- Used VGG16 model with small modification to the last set of layers
- Achieved 94% validation set accuracy
- Used data augmentation to capture different perspectives of the same image, multiple times over
- Used batch normalization to reduce the computational performance hit
- Batch normalized with data augmentation yielded 56% accuracy trained over 10 epochs
