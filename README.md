# Inside-Vehicle-Action-Detection

## Summary
In this project,human action detection inside vehicle is studied by utilizing a convolutional neural network (CNN) based on transfer learning, where a model trained on large scale dataset(ImageNet) is reused to transfer its knowledge to overcome the shortage of training data in the target domain. CNN is applied to learn the important spatial features of the input images associated with a particular participants action inside vehicle and perform the classification task. Various pretrained CNN architectures are explored and studied. Moreover, the effect of transfer learning and data augmentation is also carefully analyzed. 

### Data Collection 
Around 17 participants have involved in the data collection process including male and female. Actual vehicle environment is used to collect the data during day time condition.The participants were instructed to perform all the actions accordingly. Meanwhile, RGB sensor mounted on the front side(inside the vehicle) is used to capture the participant maneuvers.  

## Training Tools 
- Tensorflow and Keras framework 
- Python 3.5
- Ubuntu 18.06
- NVIDIA GeForce TITAN GPU
