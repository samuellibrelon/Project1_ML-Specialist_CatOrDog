# Project1_ML-Specialist_CatOrDog

This is an image classification project using a convolutional neural network model (VGG16) with transfer learning. The objective of the project is to classify images of cats and dogs using machine learning.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- Numpy
- Google Colab (optional, recommended)

## Project Structure

```plaintext
Project1_ML-Specialist_CatOrDog/
├── data/                # Directory containing training and testing data
│   ├── train/           # Training images (cats, dogs)
│   └── test/            # Test images (cats, dogs)
├── notebook/            # Jupyter notebook or Python script for training
├── models/              # Saved trained models
└── README.md            # Project documentation

```
## How to Run the Project on Google Colab

Follow these steps to run the project on Google Colab:

1. **Access Google Colab**  
   Open [Google Colab](https://colab.research.google.com/) in your browser.

2. **Upload the code**  
   Upload the notebook or Python script (`notebook/` directory) to the Google Colab interface.

3. **Upload the data**  
   Upload the image dataset (cat and dog images) directly to Colab or ensure that the correct path to the dataset is specified in the code.

4. **Run the training code**
   Execute the cells in the notebook to start training the model. This process will:

  - Load and preprocess the images.
  - Train the VGG16 model with adjusted final layers for binary classification (cat or dog).
  - Evaluate the model's performance.

5. **Check the results**
  After the training is complete, the model’s performance metrics (loss and accuracy) will be displayed. You can also use the model to predict the class of new images (cat or dog).
