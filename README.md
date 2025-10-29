# MNIST Handwritten Digit Classifier (ANN)

A simple Artificial Neural Network (ANN) built using TensorFlow and Keras to classify the MNIST dataset of handwritten digits. This project is a foundational example of building, training, and evaluating a neural network for image classification.

[Image of the MNIST dataset examples]

---

## Project Overview

The goal of this project is to build a simple neural network that can accurately recognize handwritten digits from 0 to 9. It uses the classic MNIST dataset, which contains 60,000 training images and 10,000 testing images, each 28x28 pixels.

---

## 🛠️ Technologies Used

* **Python**
* **TensorFlow** & **Keras** (for building and training the model)
* **NumPy** (for numerical operations)
* **Matplotlib** (for plotting training results)

---

## 🚀 Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

You will need Python 3.x and pip installed on your machine.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR-USERNAME/mnist-ann-classifier.git](https://github.com/YOUR-USERNAME/mnist-ann-classifier.git)
    cd mnist-ann-classifier
    ```
2.  **Create and activate a virtual environment (recommended):**
    ```bash
    # On macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    
    # On Windows
    python -m venv venv
    .\venv\Scripts\activate
    ```
3.  **Install the required packages:**
    *(You should create this file by running `pip freeze > requirements.txt`)*
    ```bash
    pip install -r requirements.txt
    ```

---

## 🏃 Usage

To train and evaluate the model, simply run the main script:

```bash
python main.py
