# Reproducibility Study of U-Net: Convolutional Networks for Biomedical Image Segmentation  

### Description
- The U-Net model, originally designed for biomedical image segmentation, has shown remarkable performance in various image segmentation tasks.  
- This study tests the generalizability of the U-Net model by applying it to a different domain: land cover classification using the DeepGlobe Land Cover dataset.

### Data  
- The DeepGlobe Landcover dataset
- Number of training examples: 803  
- Number of validation examples: 171  
- Number of test examples: 172  
- Classes: Urban, Agriculture, Rangeland, Forest, Water, Barren, and Unknown.  

### Hyperparameter  
- Learning rate: 0.0001  
- Batch size: 4
- Number of epochs: 10  
- Optimizer: AdamW

### Experimental setup
- The experiments were conducted using PyTorch.  
- The model was trained and evaluated using Focal Loss as loss function and IoU as evaluation function.  

### Result
- The IoU result is 0.4213.
- Image segmentation result  
- <img width="206" alt="image" src="https://github.com/Teemyteem/Unet_DeepGlobe/assets/129394136/32f3199f-ab8f-4b3a-9ef5-73ad2551357d">


