
Project Overview

This project focuses on analysing finger-tapping signals to support the detection of Parkinson’s Disease using machine learning techniques. The primary objective is to transform raw sensor data into structured, high-quality datasets suitable for deep learning models.

This repository contains the data preprocessing pipeline, including signal cleaning, normalisation, and sequence preparation.

My Role

Data Cleaning & Feature Extraction Specialist (Domain Role)


Cleaning raw finger-tapping signals
Removing noise and inconsistencies
Normalising signal values
Structuring time-series data
Preparing inputs for feature extraction and deep learning models

This stage is critical as it directly affects model accuracy and reliability.

Pipeline Overview


The notebook implements the following steps:

1. Data Loading
Import raw tapping signal files
Handle multiple formats and datasets
2. Data Cleaning
Remove noise and irregular spikes
Handle missing or inconsistent values
Ensure signal stability
3. Normalisation
Scale signal values to a consistent range
Improve comparability across samples
4. Signal Validation
Visualise raw vs cleaned signals
Ensure data quality is preserved
5. Sequence Transformation
Convert signals into time-series format
Prepare long-format dataset
6. Padding
Standardise sequence length
Prepare input for deep learning models (e.g., LSTM)
7. Data Export
Save processed datasets for modelling
   Example Output
Cleaned and normalised signals
Structured time-series dataset
Padded sequences ready for training
Technical Concepts

This project applies concepts from:

Time-series analysis
Signal processing
Machine learning preprocessing
Feature engineering for biomedical data
