# DOG BREED CLASSIFIER

## Data
Sample images.
![Alt text](./Images/Curly-coated_retriever_03896.jpg?raw=true)
## Model
CNN based transfer learning. 

Used InceptionV3 as the base model for feature extraction and added additional classification fully connected layers for classification among differnet dog breeds.

## Criterion and Optimizers

Criterion: Cross Entropy Loss

Optimizers: Stochastic Gradient Decent (learning rate = 0.1)

## Training and Loss

Cross validation applied to avoid over fitting. Validation loss 0.48 at the end of 20 epochs.

## Result

The model reached a accuray of 89%, test loss : 0.34.

 
