# Inside-Vehicle-Action-Detection

## Summary
In this project, Detection of human action inside vehicle is studied by utilizing transfer learning, where a model trained on large scale dataset(ImageNet) is reused to transfer its knowledge to the smaller datasets. Around 17 participants has involved in the data collection process. A convolutional neural network(CNN) is applied to learn the important features of the participant inside a vehicle and classifiy the activities. Various pre-trained CNN architectures are explored and, the effect of transfer learning and data augmentation is also carefully analyzed. 

### Data Collection 
The data is collected by recuriting around 17 participants including male and female. A real vehicle is utilized to collect the all thedata during day time condition. Particulary, RGB sensor mounted on the front side(inside the vehicle) is used to effectively collect the participants movements. 

## Training Tools 
Tensorflow and Keras framework 
Python 3.5
Ubuntu 18.06
NVIDIA GeForce TITAN GPU
