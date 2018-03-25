# NEURAL NETWORK - SMARTHPHONE 

* Applied Neural Network Machine Learning to Predict human activity using smartphone sensor data.

Link for the data: http://archive.ics.uci.edu/ml/datasets/Smartphone-Based+Recognition+of+Human+Activities+and+Postural+Transitions

## The Dataset

The experiments were carried out with a group of 30 volunteers within an age bracket of 19-48 years. They performed a protocol of activities composed of six basic activities: three static postures (standing, sitting, lying) and three dynamic activities (walking, walking downstairs and walking upstairs). The experiment also included postural transitions that occurred between the static postures. These are: stand-to-sit, sit-to-stand, sit-to-lie, lie-to-sit, stand-to-lie, and lie-to-stand. All the participants were wearing a smartphone (Samsung Galaxy S II) on the waist during the experiment execution. We captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz using the embedded accelerometer and gyroscope of the device. The experiments were video-recorded to label the data manually. The obtained dataset was randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of 561 features was obtained by calculating variables from the time and frequency domain. See 'features_info.txt' for more details. 

This dataset is an updated version of the UCI Human Activity Recognition Using smartphones Dataset that can be found at: [Web Link] 
This version provides the original raw inertial signals from the smartphone sensors, instead of the ones pre-processed into windows which were provided in version 1. This change was done in order to be able to make online tests with the raw data. Moreover, the activity labels were updated in order to include postural transitions that were not part of the previous version of the dataset. 


## Data Pre-Preocessing 
Note: This dataset has already been scaled

* Red the test and training data
* Converted the data into array for Keras ML library
* One-hot encoded integer lables (this step is already done)

## Create Deep Learning Model
* Created Machine Learning model
* Added hidden aand out put activation layers by using 'relu' and 'linear' 
* Compiled the model
* Fit the model

## Saved the Trained Model and Evaluated it
* Test the accuracy and Normal Neural Network Loss

## Predictions 
* Used the model to test the testing data to make predictions

## Conclusion 
* Made a prediction with one data point (1,561) array
* With 94% of accuracy, the prediction was made which was STANDING for this data point. 

## Tools Used for this case
* Pyton
* Pandas
* Numpy
* Sklearn
* Keras 
* Machine Learning tools 
* Neural Network tools 
