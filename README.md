# CNN_kaggle_dataset
 Convolutional Neural Network (CNN) is implemented using the Keras library for image classification on a dataset containing images of landscapes divided into six classes: buildings, forest, glacier, mountain, sea, and street. The model architecture consists of three convolutional layers with batch normalization, max-pooling, and dropout to prevent overfitting. It is followed by fully connected layers with batch normalization and dropout, ending with a softmax layer for multi-class classification.

The data is augmented using the ImageDataGenerator, which performs operations like rotation, horizontal and vertical shifts, and flipping to artificially increase the size of the training dataset. The model is trained using the Adam optimizer and categorical crossentropy loss. Training progress is monitored with ReduceLROnPlateau, which reduces the learning rate if validation loss plateaus, and EarlyStopping to halt training if there is no improvement.

After training for 15 epochs, the model achieves a validation accuracy of approximately 84.83%. The training and validation loss and accuracy are visualized using matplotlib. However, an issue is encountered when attempting to plot the loss, resulting in a KeyError for "loss." It is suggested to either add the loss metric to the model's compile method or use a different key such as "val_loss" for plotting.

Finally, a few images from the prediction set are randomly selected and displayed along with their predicted classes, demonstrating the model's performance on unseen data.
