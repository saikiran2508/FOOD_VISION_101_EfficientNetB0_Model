# FOOD_VISION_101_EfficientNetB0_Model
### The Accuracy Of the model is: 79.2%
### TensorBoard Results: https://tensorboard.dev/experiment/J893KfgDSRyjVwiD8Axr3w/#scalars

#### Build a Machine Learning model that can predict a food item from 101 different food classes.
#### In this model, I used the EfficientNetB0 model from TensorHub. It is a transfer learning model proven to work best for my kind of dataset.
#### I also used mixed precision training to speed up the computation process. Using mixed precision training can improve your performance on modern GPUs by up to 3x.
#### First I built a feature extraction model and based on the feature vector I fine-tuned the layers and built a fine-tuning model that has a better accuracy than the feature extraction model.
#### In this model, we used different callback functions such as TensorBoard_callback, Model_Checkpoint_callback, Early_stopping_callback, Reduce_LearningRate_callback 
