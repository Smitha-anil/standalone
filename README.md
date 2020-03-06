# standalone denoising
This is a simple python program which performs denoising using fast non-local means algorithm. Input can be an image which is noisy (Additive white gaussian). Input can also be a random color image and in this case, the program adds AWGN to the input image and performs denoising. 


# Python code
The reference python code is standalone.py
To create your own standalone project use pyinstaller on Linux platform. 
Example: pyinstaller standalone.py --onefile.


# How to test?
Download the standalone zip folder. Extract the files. Open terminal and browse to the location od sit folder inside sandalone directory. 

Execute as :  ./standalone_trial

Input 1: If input image is noisy 
Input 2: If gaussian noise has to be added to image 

Input file: Enter complete path and image name for example - /home/Desktop/images.jpeg

Press ESC to terminate the program 


# Functions used
The code uses fastnonlocal means alogithm to perform denoising using open cv libraries. 

