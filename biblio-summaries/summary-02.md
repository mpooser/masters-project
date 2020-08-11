# **A Framework for Evaluating Land Use and Land Cover Classification Using Convolutional Neural Networks** - Summary

- Validation framework for comparing different models could be improved with the use of a standard validation procedure for ML
- Validation procedure based on cross-validation and its subsequent statistical analysis
- Authors propose a general CNN, with a fixed architecture and parameterization, to achieve high accuracy on LULC classification over remote-sensor (RS) data from different sources (such as radar and hyperspectral)
- Furthermore, they present a methodology to perform a rigorous experimental comparison between the proposed DL method and other ML algorithms (such as SVM, Random Forests, & KNN)
- Used five publicly available datasets for the study:
    - 3 hyperspectral datasets:
        - Indian Pines
        - Pavia University
        - Salinas
    - 2 radar datasets (from JPL AirSAR):
        - San Francisco
        - Flevoland
    - Comprise a diverse selection of different environments (urban and rural) with different sizes, resolution, and number of classes
- Used a patch-based approach
- Objective is to perform 2D convolution over the complete 3D input volume: uses 2D CNN
- Found that CNNs give a more stable behavior for classification of all classes, regardless of their distribution
- More info to come...
