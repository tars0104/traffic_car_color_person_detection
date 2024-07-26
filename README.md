# STEP-BY -STEP GUIDE TO USE THE DETECTION MODEL FOR COUNTING CARS, FEMALES AND MALES IN A TRAFFIC AS WELL AS THE COLOR OF THE CARS-

clone the repository and unzip 
store all the files in a single folder 
Make sure to download the following datasets-
1. https://www.kaggle.com/datasets/landrykezebou/vcor-vehicle-color-recognition-dataset (Car colors)
2. https://www.kaggle.com/datasets/jangedoo/utkface-new (if you unzip use the cropped aligned folder version for ensuring better accuracy of your model as the images are approriately cropped)
Download the keras files from the following links-
1. https://drive.google.com/file/d/101I6ZYO--jMEKSV7m4TtxPTncMGNNEcB/view?usp=drive_link
2. https://drive.google.com/file/d/1R0gZutPStAZYfVGE8Id5sVB4aFo6Y4St/view?usp=drive_link
If using vs code- open the directory where you will store the files and open the gui.py file
Then in the terminal type in "streamlit run cargui.py"
An interface will open wherein you can upload an image in jpg, jpeg or png format
It will automatically detect the number of cars, females, males and the color of cars with detecting red as blue and blue as red.

# IMPORTANT NOTE
This project uses the MobileNet-SSD architecture compatible with cv2 dnn module for object detection.

- [MobileNet-SSD](https://github.com/chuanqi305/MobileNet-SSD) by chuanqi305 is licensed under the Apache License 2.0.
- [Caffe](https://github.com/BVLC/caffe) by BVLC is licensed under the BSD 2-Clause License.

The authors and contributors are acknwoledged for providing these valuable resources.
