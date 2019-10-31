This folder contains 3 subfolders and 3 files.

1. The crop_image folder contains the image crop of the detected objects with maximum dice and will be used as test
images for our classification

2. The test_image folder contain the test images we used for our localization. It now has 500 pictures selected
from the MIO-TCD-Localization\train folder. The reason we used images from this folder is because it has 
ground_truth labels in the 'gt_train.csv' file.

3. The xml folder contains all our Haar cascade models. 

4. The '(iii) Localization & Classification.ipynb' is the python file we implement our localization. It should
contain the test results of using 500 images.

5. The 'crop_img_label.csv' file contains the labels for the cropped image, which will be used as ground truth
after we passed our crop_images into our classification.

6. The gt_test file contains all the ground truth we need for the 500 images for the localization.

