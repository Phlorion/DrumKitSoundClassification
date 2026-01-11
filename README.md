# Drum Kit Sound Classification

![NumPy Badge](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=fff&style=for-the-badge)
![pandas Badge](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=fff&style=for-the-badge)
![scikit-learn Badge](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=fff&style=for-the-badge)

A machine learning project for classifying drum kit sounds using audio feature extraction and supervised/unsupervised learning techniques.

## What the Project Does

This project implements a sound recognition system that classifies four types of drum kit sounds:

- Kick drum
- Clap
- Snare drum
- Hi-Hat

The system uses Mel-Frequency Cepstral Coefficients (MFCCs) extracted from audio waveforms as features, then applies various machine learning algorithms for classification.

## Why the Project is Useful

- **Audio Feature Extraction**: Demonstrates how to convert raw audio files into numerical features suitable for machine learning
- **Sound Classification**: Shows practical implementation of multi-class classification on audio data
- **ML Techniques**: Includes both supervised (e.g., neural networks) and unsupervised (e.g., clustering) learning approaches
- **Educational Value**: Serves as a complete example of an end-to-end machine learning pipeline for audio processing

## Getting Started

### Prerequisites

The project requires the following Python libraries:

- numpy
- pandas
- matplotlib
- scikit-learn
- librosa

### Data

The processed data is already included in the `data/` directory. Each sound type has its own folder containing MFCC features in CSV format.

If you want to process raw audio files yourself, see the preprocessing notebook.

### Usage

1. Open `sound_recognition.ipynb` in Jupyter Notebook
2. Run the cells to load data, train models, and evaluate performance
3. The notebook includes both supervised and unsupervised learning examples

## Project Structure

- `preprocess_data.ipynb`: Audio preprocessing and MFCC feature extraction
- `sound_recognition.ipynb`: Main machine learning implementation
- `data/`: Processed MFCC features for each sound type
- `raw_data/`: (Not included) Original WAV files used for preprocessing

## Where Users Can Get Help

This is a course project for the Machine Learning course at Athens University of Economics and Business (AUEB) Department of Informatics, Winter semester 2024-2025.

For questions about the implementation refer to the maintainer of this project.

## Who Maintains and Contributes

**Maintainer**: George Avrabos (Phlorion)

This project was developed as part of a university assignment. Contributions are welcome for educational purposes.
