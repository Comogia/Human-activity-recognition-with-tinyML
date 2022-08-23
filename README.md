# Human-activity-recognition-with-tinyML
The aim of this project is to classify the human activity using machine learning model

The first step I made was to create a standard tensorflow model, after that I converted it
with TinyML, a library that reduce the dimension of the model in order to use it on device
with limited memory.

My last step consisted in reducing the model further through a process called quantization.
I compared the accuracy and the dimensions of the 3 Machine Learning model.

I have used two different dataset, the first one is a dataset created by myself with the data
received from an Arduino Nano 33 BLE.
The second one is a UCI dataset, an experimental dataset by the University of Genova
and Universitat Politècnica de Catalunya.

The Arduino board has a bluetooth connectivity which I used to connect Arduino to my
smartphone to allow it to receive the values measured while I was doing the two activities,
running and walking.

As a result I got the values of the three axis of both accelerometer and gyroscope.
During my work I was supported by a book “TinyML” edited by O’Reilly and also the tutorial
on the Arduino website .
