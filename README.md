# AI Driving Classification

## Project Overview
This project investigates the use of Artificial Intelligence (AI) and Deep Learning (DL) techniques to analyze and classify different driving behaviors using sensor data collected from mobile devices. The study focuses on Recurrent Neural Networks (RNN), particularly Long Short-Term Memory (LSTM) architectures, to develop a system capable of classifying driving behaviors such as acceleration, braking, cornering, and navigating roundabouts.

### Motivation
The motivation for this project is to enhance road safety by analyzing driving behaviors in real-time using the sensors available in smartphones. The goal is to create an accessible and effective solution for detecting and classifying various driving styles, thereby contributing to accident prevention and promoting responsible driving.

### Authors
- Alberto Pingo ([@albertopingo](https://github.com/albertopingo))
- João Castro ([@jcastroo](https://github.com/jcastroo))


# Methodology
The project is approached from two perspectives:

First Approach: Analyzes data from a complete trip by segmenting sensor data (accelerometer, gyroscope) to classify driving patterns over an entire journey. Architectures such as Stacked LSTM, Bidirectional LSTM, and Convolutional LSTM were applied.

Second Approach: Focuses on specific driving scenarios like acceleration, braking, and cornering, with pre-classified driving styles as "Slow," "Normal," and "Aggressive." This approach allows the development of models that can classify diverse behavior patterns in different driving situations.

### Key Technologies
Python: The primary programming language used for model development.

TensorFlow & Keras: Libraries used for building and training the neural network models.

Pandas, NumPy, Matplotlib, Seaborn: For data manipulation, analysis, and visualization.

### Key Directories
- datasets/: Contains the datasets used for training and testing the models.
- code/: Contains Jupyter notebooks and models for both approaches.
  - first-approach/: Code for analyzing a complete trip using various LSTM architectures.
  - second-approach/: Code for specific driving scenarios classified into "Slow," "Normal," and "Aggressive."
- extras/, others/, publications/: Additional resources, references, and publications related to the project.

## System Info
- **Operating System:** Ubuntu 22.04 LTS
- **Python Version:** 3.11.4
- **CPU:** i5 4690k
- **GPU:** NVIDIA GTX 1060 6GB
- **RAM:** 16GB DDR3

## Libraries used
- **os**
- **json**
- **numpy:**        1.26.4
- **pandas:**       2.2.2
- **matplotlib:**   3.9.0
- **seaborn:**      0.13.2
- **tensorflow:**   2.15.0
- **keras:**        2.15.0
- **scikit-learn:** 1.5.0
- **scipy:**        1.13.1

## CUDA and cuDNN

- **CUDA Version:** 12.4
- **cuDNN Version:** 8.9.4.25

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.



