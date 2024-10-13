# Speech Emotion Recognition (SER) Project

## Project Overview
This project is a Speech Emotion Recognition (SER) system that aims to identify emotions expressed in speech by analyzing audio data. <br> The project focuses on preprocessing audio data, extracting relevant features, and building a model to classify emotions such as anger, happiness, sadness, and more based on the acoustic properties of the speech signals.

## Dataset Information
There are a set of 200 target words were spoken in the carrier phrase "Say the word _' by two actresses (aged 26 and 64 years) and <br> recordings were made of the set portraying each of seven emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral). <br> There are 2800 data points (audio files) in total.

The dataset is organised such that each of the two female actor and their emotions are contain within its own folder. <br> And within that, all 200 target words audio file can be found. The format of the audio file is a WAV format

## Output Attributes
- anger
- disgust
- fear
- happiness
- pleasant surprise
- sadness
- neutral

## Project Features
- __Audio Processing:__ Uses librosa to load and process the audio files, extracting essential features such as Mel-frequency cepstral coefficients (MFCCs), chroma, and mel spectrogram.
Data Visualization: Employs libraries like seaborn and matplotlib to visualize audio waveforms, spectral properties, and other feature distributions.
Emotion Classification: The project aims to classify the emotions based on the extracted audio features using machine learning algorithms.
#### Libraries Used
- __Python:__ The project is implemented using Python.
- __NumPy:__ For numerical operations.
- __Pandas:__ For handling dataframes and data manipulation.
- __Librosa:__ For loading, playing, and analyzing audio signals.
- __Matplotlib/Seaborn:__ For data visualization.
- __IPython.display.Audio:__ For playing audio within the notebook.
- __OS:__ For navigating and accessing files from directories.

