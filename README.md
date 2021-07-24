# ASL-Recognition-Using-CNN
Major Project; 
Simple and easy to use

# Software Specification
1. Tensorflow
2. Opencv
3. Numpy

# Process Explanation
1. The first thing I did was, I created 26 gesture samples using OpenCV. For each gesture I captured 500 images which were 50x50 pixels. All theses images were in grayscale which is stored in the gestures/ folder. The pictures were flipped using flip_images.py.
2. Before running this project you should have basic knowlede about OpenCV, Tensorflow, and Numpy is and how it works.
3. Created a CNN which look a lot similar to this MNIST classifying model using Tensorflow. If you want to add more gestures you might need to add your own layers and also tweak some parameters, that you have to do on your own.
4. Then used the model which was trained using Tesorflow on a video stream.
5. As of today, I have stored the 26 gestures for which are 26 alphabets of American Sign language. And trained the model on these images.

# How To Run
1. After downloading the repository, first run img_cap.py to add/capture gesture.
2. Then make changes in the dataset.py file in the clasess line, and run dataset.py to create train_data.npy.
3. Now run the train.py, which will train the data with the use of cnn_sgn.py in your PC.
4. After training the data, finally run the output.py, which will open the window for gesture recognition.

# Thank You
