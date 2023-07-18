# Neural Networks and Deep Learning - Summer of Science 2023

This repository contains projects completed during the "Neural Networks and Deep Learning" course organized by the Maths and Physics Club for the Summer of Science 2023.

## Projects:

### 1. MNIST Digit Identification
- File: `MNIST_Digit_Identification.ipynb`
- Description: This notebook showcases a digit identification project using the popular MNIST dataset. The model achieved an impressive accuracy of 98.94%.
- **References**:
    1. [TensorFlow Functional API](https://www.tensorflow.org/guide/keras/functional_api)

### 2. Cat vs Dog Classifier
- File: `CatDogClassifier.ipynb`
- Description: This notebook presents a cat vs dog classification project. The model, trained on the `cats_vs_dogs` dataset by TensorFlow, achieved an accuracy of 79.55%.

- **References**:
    1. [TensorFlow Datasets - Cats vs Dogs](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs)
    2. [Classify Images of Dogs and Cats using CNN and TensorFlow 2](https://lindevs.com/classify-images-of-dogs-and-cats-using-cnn-and-tensorflow-2)

### 3. Image Super Resolution with Pixel Shuffle
- File: `ISR_with_Pixel_Shuffle.ipynb`
- Description: This notebook implements Sub-Pixel CNN with Residual Dense Blocks for image super resolution. The accuracy was measured using PSNR (Peak Signal to Noise Ratio), resulting in a validation loss of 0.0021 and a validation PSNR of 25.61. The test predictions demonstrate satisfactory results.

- **References**:
    1. [Pixel Shuffle Super Resolution with TensorFlow, Keras, and Deep Learning](https://pyimagesearch.com/2021/09/27/pixel-shuffle-super-resolution-with-tensorflow-keras-and-deep-learning/)
    2. [Sub-Pixel CNN with Residual Dense Blocks - Research Paper](https://arxiv.org/abs/1609.05158v2)
  
***Note**: The projects `Cat vs Dog Classifier` and `Image Super Resolution with Pixel Shuffle`, are computationally intensive. For optimal performance, it is recommended to run these notebooks on a GPU. On Google Colab, the GPU can be accessed via `Runtime > Change runtime type > Hardware Accelerator > GPU`.*

