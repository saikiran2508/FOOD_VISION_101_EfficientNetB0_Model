# FOOD_VISION_101_EfficientNetB0_Model
### The Accuracy Of the model is:

Build a Machine Learning model which can predict a food item from 101 different food classes.
In this model I used EfficientNetB0 model from TensorHub. It is a transfer learning model which is proven to be working best for my kind of dataset.
I also used mixed precision training to speed up the computation process. Using mixed precision training can improve your performance on modern GPUs by up to 3x.
First I build a feature extraction model and based on the feature vector I fine tuned the layers and build a fine tuning model which has a better accuracy than the feature extraction model.
In this model we used different callback function such as: TensorBoard_callback, Model_Checkpoint_callback, Early_stopping_callback, Reduce_LearningRate_callback 
