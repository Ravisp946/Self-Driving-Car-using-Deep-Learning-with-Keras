# Self-Driving-Car-using-Deep-Learning-with-Keras
This is a model for self driving car made using Keras which is trained and tested on simulator provided by UDACITY.

The Final Code of this Self Driving Car(Behavioural_Cloning.ipynb) uses the technique of Polynomial Regression to predict the correct Throttle 
and Steering angle of the car whose data was collected using the UDACITY simulator.

Link for the Simulator-https://github.com/udacity/self-driving-car-sim

Nvidia Model was used to train the network on the training data collected.

Traffic Sign Classification is not used in Final code but it will be used in future project where the self driving need to identify different traffic signs and needs to decide what to do.

Finally to connect to the simulator and test our saved model we use drive.py which basically consist of Flask and Socket I/O techniques to connect ot simulator.
You can initialize the speed of the car in that file.

Play around the different parameters of code to get better results and achieve high accuracy.

THESE FILES WERE RUN ON GOOGLE COLAB EXCEPT THE drive.py
