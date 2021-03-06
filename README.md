# Self-Driving-Sim

This project was built with the help of a Siraj Raval video found here: https://www.youtube.com/watch?v=EaY5QiZwSP4

## The What
In this project I built a model to autonomously drive a car in a car simulation made for the Udacity Self-Driving car nanodegree Program found here: [Udacity Program](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013).
The link to clone and run the simulation can be found here [simulation](https://github.com/udacity/self-driving-car-sim).
The simulator was used to record training data for this project. 

# The Files
## model.py
  This files takes the training data from the simulator to train a convolutional neural network and produce an .h5 file
 
## drive.py
  This file is used to communicate with the simulator running in autonomous mode. The data is gathered from the simulator and fed through the model which sends back the predicted steering angles for real time driving. 
  
# To run using my model
1. dowload dependencies: 
```
conda env create -f environments.yml 
```
2. start simulator running in autonomous mode

3. run drive.py with my model
```
python3 drive.py model.h5
```
  
