# Smart Glove Gesture Recognition

Implementation of gesture recognition using CNN based on the paper ["Machine Learning-Based Gesture Recognition Glove: Design and Implementation"](https://doi.org/10.3390/s24186157) (Sensors 2024).

## Overview
This repository contains Google Colab implementation for recognizing five gestures (fist, double tap, finger spread, wave left, wave right) using sensor data from a smart glove equipped with:
- 5 flex sensors
- 5 pressure sensors
- IMU sensor (orientation and acceleration)

## Features
- Data preprocessing for multiple sensor inputs
- CNN model with three 2D convolutional layers
- 90% classification accuracy
- Real-time capable gesture recognition

## Usage
1. Open the notebook in Google Colab
2. Upload your sensor data CSV file following the provided format
3. Run all cells to train and evaluate the model

## Model Architecture
- Input layer handling multiple sensor data streams
- Three Conv2D layers with ReLU activation
- Batch normalization
- Dense layers with dropout
- Softmax output for 5-class classification

## Requirements
- TensorFlow 2.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Citation
```bibtex
@Article{s24186157,  
    title="Machine Learning-Based Gesture Recognition Glove: Design and Implementation",
    author="Filipowska et al.",
    journal="Sensors",
    year="2024",
    volume="24",
    number="18",
    pages="6157"
}
```

## License
MIT License

Feel free to use and modify the code for your projects!
