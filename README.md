# Requirements

Assessment of preprocessing techniques on performance of medical image segmentation

Each individual should write a program with Graphic User Interface that perform following step

- [x]  Select/Choose image
- [x]  Save the preprocessed and segmented images
- [x]  Display the chosen image's histogram
- [x]  Preprocessing:
    - [x]  average and median filtering;
    - [x]  histogram equalization kernel_size = 3 by default
        - [ ]  size and shape of the mask should be selected.
- [x]  Calculate and display corresponding PSNR values
- [ ]  Segmentation:
    - [x]  minimize probability of error (Kapur method)
        - [ ]  own implementation
    - [x]  and maximize variance between class (Otsu method)
        - [ ]  own implementation
- [ ]  Evaluate and display segmentation performance in terms of
    - [ ]  sensitivity,
    - [ ]  specificity and
    - [ ]  accuracy,
    - [ ]  FPpI (False Positives per Image) with different preprocessing methods

**Note**

- Data for evaluation:
    
    https://www.kaggle.com/datasets/awsaf49/cbis-ddsm-breast-cancer-image-dataset
    
- Try to code yourself. Do not use available functions for at least for segmentation tasks.
- Self report should include: captures of results for several images; final assessment on whole dataset; discussions on effectiveness on different type of images (high, medium, small density)
