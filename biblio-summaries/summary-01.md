# **Dense Fusion Classmate Network for Land Cover Classification** - Summary

- Addresses the missing mid-level structure information in satellite imagery
- Paper proposes a Dense Fusion Classmate Network (DFCNet)
- Jointly trained with auxiliary road dataset deemed as "classmate" (compensates mid-level information)
- Dense fusion module: guarantees precise discrimination of confused pixels and benefits the network optimization from scratch
- Semantic segmentation (the overall task of LULC) requires predictions be made at every pixel
- Three methods to improve semantic segmentation:
    - encoder-decoder architecture
    - feature fusion
    - strengthening the spatial information
- Remote sensing scenes have their own characterstics so general semantic segmentation may not be completely feasible
- Paper aims to make the following contributions:
    1. Propose a classmate strategy which successfully combines two seemingly unrelated task datasets and obtains obvious improvement on specific task
    2. Adopt a dense fusion module
    3. Provide a meaningful perspective that road class is an strong compensate for other land cover classes. Can use road distribution as a form of structure
- Dataset: DeepGlobe Land Cover Classification and Road Extraction
    - 5000 images of road training dataset: 1024x1024
    - 600 images of land training dataset: 2448x2448
    - 203 images of land dataset: used for testing
