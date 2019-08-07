# lipsticks_detect
Identify the brand, series, id and color of the lipstick
# Dataset
The data is in the form of a json string with a total of 271 lipstick numbers, 5 brands including Saint Laurent, Miss Chanel Coco, Dior, Maybelline, Givenchy, and the color id and name of the different lipstick numbers under each lipstick brand series. , and hexadecimal color values.<br>
the name of the dataset file is lipstick.json
# Installation
* Python36
* Dlib(to import Dlib you should Download the corresponding version of the wheel file, the file directory shows the dlib-19.5.1-cp36-cp36m-win_amd64.whl file, you should go to the directory and use the pip install command to download dlib)
* numpy
* cv2
# To start
* run the detect.py file, face recognition, and save the two lips images captured in the Output folder
* then run the test.py file to extract the colors in the image, traversing the dataset output the most likely three Lipstick information
# Notice
Due to the different lipstick numbers, the RGB components account for different proportions. You need to adjust the code for comparing the time component errors in the test.py file.
