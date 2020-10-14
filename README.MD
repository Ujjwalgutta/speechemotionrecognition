# Speech Emotion Recognition
Communication based on emotions is an important capability. Detecting the emotional state of a speaker from speech aids in extraction of important semantic information. Automatic speech emotion recognition is a challenging task due to the
discontinuity between acoustic features and human emotions.

## Motivation
- To achieve truly effective HCI interaction, there is a need for computers to be able to interact naturally with humans.
- ‘Behavioural Biometrics’ is an upcoming field which deals with utilizing behaviour information like emotions as these traits are impossible to steal.

## Features Used
- Mel-frequency Cepstral Coefficients (MFCCs)
- Spectral Contrast
- Spectral Flatness
- RMS Energy
- Zero-Crossing Rate
![Alt Text](Images/mfcc.PNG)

## Data Pipeline
Workflow of the project is as follows:
![Alt Text](Images/pipeline.PNG)

## Results
Accuracy, f-score and Recall values of different models were calculated. 
![Alt Text](Images/results.PNG)

Multi Layer Perceptron out performed other models due to limited availability of training data.

## Analysis
#### Confusion Matrices
Multilayer Perceptron                                         |   Convolutional Neural Network
:-------------------------:|:-------------------------:
<img src="Images/MLP-RAVDESS.png" width="400" height="400">   |   <img src="Images/CNN-RAVDESS.png" width="400" height="400">          
Random Forest Classifier                                      |   Support Vector Machine
<img src="Images/RFC-RAVDESS.png" width="400" height="400">  |   <img src="Images/SVM-RAVDESS.png" width="400" height="400"> 

#### Feature-Based Accuracy Comparison
![Alt Text](Images/FBAC.PNG)

 

