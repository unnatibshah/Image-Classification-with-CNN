# Image-Classification-with-CNN
In this project, I will create and train a CNN model on a subset of the popular CIFAR-10 dataset. The same technique can be used to solve image classification problems on your own data as well.

Project Structure:

1: Importing the required libraries and helper functions.

2: Pre-process Data
Importing the CIFAR-10 dataset.
Creating a subset of the dataset which has just 3 classes instead of 10. This is done for both the training and test set.
Randomly shuffling the newly created subset.

3: Visualize Examples
Plotting randomly selected examples of a given set.
We look at some examples from training and test set along with their labels.

4: Create Model
Creating a Keras Sequential model.
Creating a function to add a convolutional block to the model.
A look at the model summary.

5: Train the Model
Fit the model on the subset.
Setting the EarlyStopping callback.
Setting the ModelCheckpoint callback.

6: Final Predictions
Plotting the training and validation accuracy from the training.
Loading the best model.
Getting predictions on the test set and displaying the results.
