# MNIST-Digit-Recognizer

The [MNIST dataset](http://yann.lecun.com/exdb/mnist/) provides a training set of 60,000 handwritten digits and a validation set of 10,000 handwritten digits. The images have size 28 x 28 pixels. Therefore, when using a two-layer perceptron, we need 28 x 28 = 784 input units and 10 output units (representing the 10 different digits).

**Note: It can Only Predict Digits from 0-9 Only.**

## Requirements

As this project is basically made using Jupyter Notebook. So it requires to install [Anaconda](https://www.anaconda.com/products/individual#Downloads).

* zipfile
* pickle
* tkinter
* pandas >= 1.0.1
* sklearn >= 0.22.1
* cv2 >= 4.2.0
* pyscreenshot >= 2.2.0
* PIL >= 7.0.0

You can install any module as:

* Open Anaconda prompt or Command prompt
* Syntax : pip install module_name

**Note: Make sure to have a stable Internet Connection.**

## Instruction

After completing the requirements, following steps to be followed:

* Open the mnist_digit_model_train.ipynb to download, train and load model into a .pkl(i.e pickle) file.
* Open Tkinter-Digit Recognizer GUI.ipynb.
>* Change the variable ('folder_loc') to project directory location. 
>* Make sure model.pkl file is present in same directory.
>* Run the programe.
>* Move the GUI window to ![TOP LEFT](https://github.com/rogueui/MNIST-Digit-Recognizer/blob/master/image/image.png) corner for prediction.
>* The GUI has 3 functions:
>>1. Press & Drag LEFT CLICK to draw.
>>2. Press RIGHT CLICK to clear the screen.
>>3. Press PRIDICT BUTTON to pridict the digit.
