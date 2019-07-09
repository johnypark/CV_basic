## Computer Vision Fundamentals
This repository is for beginners in computer vision and image processing. 
https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_tutorials.html
### 1. Quantization methods 


### 2. Hitrogram streching
- https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_histograms/py_histogram_equalization/py_histogram_equalization.html#histogram-equalization


### 3. Histogram features


### 4. Grey-level Co-occurence Matrix 
#### Sources for computing GLCM and GLCM features 
- scikit image https://scikit-image.org/docs/dev/auto_examples/features_detection/plot_glcm.html

#### Theoretic basis and improvement for computing time
- Haralick original paper O(n^2)
- Unser descriptor - Sum and difference histogrames O(n)
- Implementation of User descriptor - Araujo et al. 2018. https://ieeexplore.ieee.org/abstract/document/8489705
- Implementation of User descriptor 2 - Araujo et al. 2018. https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8612847

#### Implementation
- What if ROI is non-rectangular? https://stackoverflow.com/questions/40703086/python-taking-the-glcm-of-a-non-rectangular-region
- What if ROI is non-rectangular? NaN in matlab https://stackoverflow.com/questions/8237000/the-method-of-calculate-the-glcm-of-a-specific-point-in-a-image

### 4. Local descriptors
- (2010) Texture Classification by Modeling Joint Distributions of Local Patterns With Gaussian Mixtures
- (2018) local-descriptors-for-image-classification https://github.com/vdevmcitylp/local-descriptors-for-image-classification
