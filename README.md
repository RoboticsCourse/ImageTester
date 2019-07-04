# ImageTester
An Android project used to determine discrepancies between the Python Keras Neural Network output and the Android Tensorflow ouput

## Usage
Inside the app navigate to a folder of images and select the folder once inside it.
To avoid potential problems don't put anything other than images into the folder.
When the app passes the neural network through all the images it will print a text file to the application cache file located in the file system Android folder and the app folder inside that.
This file contains values that can be compared to the values generated by the corresponding Keras code of the model used.
