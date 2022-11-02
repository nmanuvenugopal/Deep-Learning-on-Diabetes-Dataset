# Diabetes prediction using Deep Learning Models

The project covers the following task:
1. Importing of the data from the corresponding CSV files.
2. Separating the dataset to the features and labels.
3. Dividing the fetaures and labels to the training and testing dataset.
4. Normalising the dataset using StandardScalar
5. Creating a simple Deep Learning model with Input and Dense layers.
6. Since its a binary classification problem ww will be using the loss function as " binary_crossentropy" and activation function as "sigmoid" in the output layer.
7. We will use "relu" as activation function in other Dense layers.
8. Regarding optimizers we will use "Adam".
9. We will train the model and it was evident that training accuracy is very good and testing accuracy is very poor (overfitting).
10. For Removing the overfitting problem, I have applied L1 and L2 regularization technique.
11. I have also used droput layer to avoid over fitting.
