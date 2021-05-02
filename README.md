# JS_OCR_digits
this is the project folder for creating an OCR digit reader in JS... Converting from python


index.html - contains js code to process uploaded image.  This is where the openCV morphological steps are going to be debugged and developed.

OCR text.ipynb - is the python version of this process that we are converting to JS

opencv.js - the opencv.js library

1151.png - sample image to perform OCR on

## Set up:

1. run `git clone https://github.com/jude253/JS_OCR_digits` in a folder where you want the project to be located
2. click on index.html and run it in chrome (or which ever browser you choose) to run the image processing and debugging
3. edit the index.html file in your favorite code editor.

## Next we need to: 
1.countour the swelled image
2.get the bounding boxes of the digits
3.crop digits into individual images
4.convert digit lookup NN to tensorflow.js format, then embed in index.html
5.fine tune
