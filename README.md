# Image processing project
The aim of the project is to create an algorithm that detects and recognizes dutch car plates without using cv2 functions.

'Plate and character localization' allows to localize and segment out the plate and its characters in a frame.
'Bitwise comparison for character recognition' allows to recognize the segmented out chracaters.

plates folder contains some of the pictures with the cars that were used during the development and testing of the algorithm.
dataset folder contains characters that are used for bitwise comparison (for recognition). 

# Install
- Install python
- Install anaconda

# Usage

Open Jupyter notebook

### Localization
1) Go to the Plate and character localization file.
2) In Localization section, in the first cell, indicate the path to your image (file_name).
3) At the very end of the file (last cell) indicate the path to the folder where you want to save images of segmented out characters.
4) Run the code.

### Recognition
1) Make sure you have a folder with 8 pictures of segmented out characters.
2) Go to the Bitwise comparison for character recognition file.
3) Set the directory variable to the path of the folder where you have the 8 pictures of segmented out characters.
4) Run the code.

# Algorithm
In order to better understand the work of the algorithm check out the comments.

In the Report_IP file you can find a more in depth explanation of how the algorith works.
