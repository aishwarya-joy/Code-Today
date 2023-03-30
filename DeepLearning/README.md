# Deep-Learning

##HyperTuning:
  Process of selecting right parameters for the model is called hyperparameter tuning to hypertuning. Keras Tuner was used to select hyperparameters in this model for nmber of hidden layers, activation, num units etc... 
  
  
##Dataset:
Fashion-MNIST is a dataset consisting of a 60,000 samples for training 10,000 samples for testing. Each sample is a 28x28 grayscale image, associated with a label from 10 classes. There are total of 10 classes.


##Result:
Without hypertuning model was 91% accurate, while with hypertuning it increased 1%. Also to detect Unknown categories if predicted value is less than threshould, then it is categorised as None.
