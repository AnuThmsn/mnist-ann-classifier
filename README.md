# MNIST Handwritten Digit Classifier (ANN)

This project is a simple Artificial Neural Network (ANN) built using TensorFlow and Keras to classify the famous MNIST dataset of handwritten digits.

The model demonstrates a basic implementation of a sequential neural network, achieving an accuracy of **97.48%** on the test dataset.



---

## Project Workflow

1.  **Load Data:** The MNIST dataset (60,000 training images, 10,000 test images) is loaded directly from `keras.datasets`.
2.  **Preprocess Data:** Pixel values for all images (both training and test) are normalized by dividing by 255. This scales all pixel values from the 0-255 range to a 0-1 range, which helps the model train more effectively.
3.  **Build Model:** A `Sequential` Keras model is built.
4.  **Compile Model:** The model is compiled using the `Adam` optimizer and `sparse_categorical_crossentropy` as the loss function.
5.  **Train Model:** The model is trained on the training data for 10 epochs, with 20% of the data used for validation.
6.  **Evaluate Model:** The trained model's accuracy is measured on the unseen test data.
7.  **Visualize Results:** Training & validation loss and accuracy are plotted using Matplotlib.

---

## 🛠️ Technologies Used

* **Python**
* **TensorFlow**
* **Keras** (as `tensorflow.keras`)
* **Scikit-learn** (for `accuracy_score`)
* **Matplotlib** (for plotting)
* **Jupyter Notebook / Google Colab**

---

## 🧠 Model Architecture

A simple sequential ANN with one hidden layer was used.

* **`Flatten` Layer:** Converts the 28x28 pixel images into a 1D array of 784 pixels.
* **`Dense` (Hidden) Layer:** A fully-connected layer with **128 neurons** and a `relu` activation function.
* **`Dense` (Output) Layer:** A fully-connected output layer with **10 neurons** (one for each digit 0-9) and a `softmax` activation function to provide class probabilities.
