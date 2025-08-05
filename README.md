# ECG-Heartbeat-Classification-using-CNN-GRU-and-TCN-
ECG signal classification using GRU, CNN  and TCN 
Overview
# This project implements a classification model for the MIT-BIH Arrhythmia dataset using three different neural network architectures:

 GRU (Gated Recurrent Unit): A type of Recurrent Neural Network (RNN) that is used to capture the temporal dependencies in ECG signals.

TCN (Temporal Convolutional Network): A type of deep learning architecture designed to capture temporal features efficiently.

CNN (Convolutional Neural Network): A standard model used for image data but here applied to 1D ECG signals after transforming them into 2D images

# The dataset includes 5 classes:

NORM: Normal heartbeat

MI: Myocardial Infarction (Heart Attack)

STTC: ST-T Wave Abnormality

CD: Conduction Disorders

HYP: Hypertrophy

This repository contains the code to train and evaluate these models for ECG classification using the MIT-BIH dataset.

This dataset has been used in exploring heartbeat classification using deep neural network architectures, and observing some of the capabilities of transfer learning on it. The signals correspond to electrocardiogram (ECG) shapes of heartbeats for the normal case and the cases affected by different arrhythmias and myocardial infarction. These signals are preprocessed and segmented, with each segment corresponding to a heartbeat.
# Arrhythmia Dataset
Number of Samples: 109446
Number of Categories: 5
Sampling Frequency: 125Hz
Data Source: Physionet's MIT-BIH Arrhythmia Dataset
Classes: ['N': 0, 'S': 1, 'V': 2, 'F': 3, 'Q': 4]

