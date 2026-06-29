# Deep Learning Image Jigsaw Reconstruction

This repository contains the final project developed for the **Deep Learning** course at the **University of Bologna**.

## Project Overview

The objective of this project is to reconstruct an original RGB image from a set of **nine shuffled image patches**. Each image is divided into a **3×3 grid**, producing nine patches that are randomly permuted. The model learns to predict the correct arrangement of the patches and reconstruct the original image.

This task is inspired by self-supervised learning approaches that use spatial reasoning as a visual pretext task.

## Dataset

The project uses the **STL-10** dataset, which consists of:

* 100,000 unlabeled color images
* 5,000 labeled training images
* 8,000 labeled test images
* Image resolution: **96 × 96**
* 10 object categories, including airplanes, birds, cars, cats, dogs, horses, monkeys, ships, and trucks

Each image is transformed into a jigsaw puzzle by splitting it into a **3×3 grid** and randomly shuffling the resulting patches.

## Project Pipeline

* Load and preprocess the STL-10 dataset
* Generate shuffled image puzzles
* Build and train a deep learning model
* Predict the correct arrangement of image patches
* Reconstruct the original image
* Evaluate reconstruction performance

## Technologies

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Jupyter Notebook

## Results

The notebook includes:

* Data preprocessing
* Puzzle generation
* Model implementation
* Training procedure
* Prediction examples
* Reconstruction visualizations
* Performance evaluation

## Running the Project

1. Clone the repository.

```bash
git clone https://github.com/foadas/deep-learning-image-jigsaw.git
```

2. Install the required dependencies.

```bash
pip install tensorflow numpy matplotlib jupyter
```

3. Open the notebook.

```bash
jupyter notebook
```

University of Bologna – Deep Learning Course Project
