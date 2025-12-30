# Lab 1: FFNN for Network Traffic Classification

This repository contains the development of the first laboratory project, focused on the design and evaluation of **Feed-Forward Neural Network (FFNN)** architectures applied to the **CICIDS2017** dataset for cybersecurity.

## Repository Contents
* **Lab Report**: A detailed PDF document describing the architectural design, preprocessing steps, and performance analysis.
* **Jupyter Notebook**: Full Python source code covering the entire pipeline, from data exploration to handling severe class imbalance (Benign, PortScan, DoS Hulk, Brute Force).
* **Dataset (ZIP)**: Archive containing the original and processed network traffic data used for training and testing the models.

## Project Objectives
* Analysis of data bias impact (e.g., the role of the "Destination Port" feature).
* Experimentation with **Shallow** (Linear, ReLU) and **Deep** models (up to 6 hidden layers).
* Optimization via Weighted Loss, Batch Size tuning, and optimizer comparison (AdamW vs. SGD).
* Study of regularization techniques to prevent overfitting, including **Dropout**, **Batch Normalization**, and **Weight Decay (L2)**.
