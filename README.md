# Gesture_Recognition

#Problem Statement

Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

#Gesture	Corresponding Action

i) Thumbs Up	Increase the volume.

ii) Thumbs Down	Decrease the volume.

iii) Left Swipe	'Jump' backwards 10 seconds.

iv) Right Swipe	'Jump' forward 10 seconds.

v) Stop	Pause the movie.

vi) Each video is a sequence of 30 frames (or images).

#Objectives:

Generator: The generator should be able to take a batch of videos as input without any error. Steps like cropping, resizing and normalization should be performed successfully.

Model: Develop a model that is able to train without any errors which will be judged on the total number of parameters (as the inference(prediction) time should be less) and the accuracy achieved. As suggested by Snehansu, start training on a small amount of data and then proceed further.

Write up: This should contain the detailed procedure followed in choosing the final model. The write up should start with the reason for choosing the base model, then highlight the reasons and metrics taken into consideration to modify and experiment to arrive at the final model.
