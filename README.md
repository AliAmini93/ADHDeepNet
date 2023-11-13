# ADHDeepNet: ADHD Diagnosis Using EEG Data and Deep Learning

## Introduction
ADHDeepNet employs deep learning techniques and EEG signals to diagnose Attention Deficit Hyperactivity Disorder (ADHD). It integrates Convolutional Neural Networks with elements from EEGNet, Inception/Xception, and Squeeze and Excitation networks.

## Model Architecture
Inspired by EEGNet, Inception, Squeeze and Excitation, and Xception models, ADHDeepNet is specifically designed to process raw EEG signals efficiently for ADHD classification.

### Key Features
- **Efficient Processing**: Directly operates on raw EEG signals, minimizing preprocessing needs.
- **Tailored for ADHD**: Architectural modifications geared towards ADHD classification.
- **Hybrid Architecture**: Combines various proven models for enhanced performance.
- **Ablation Study**: Conducted to ensure each module and block is essential to the model architecture, validating the design choices.

## Data Augmentation
Due to challenges in EEG data collection, ADHDeepNet leverages Data Augmentation (DA) to increase the dataset's size and diversity, essential for EEG signal variability.

### Gaussian Noise Addition
- **Objective**: To improve model robustness by learning more discriminative features.
- **Method**: Perturbing raw EEG signals with random noise from a Gaussian distribution, encouraging the model to learn general patterns rather than specific training data traits.
- **Benefit**: Especially effective for EEG data, aiding the model in generalizing across diverse EEG recordings for ADHD diagnosis.

## Evaluation Methodology
- **Validation Technique**: Employs (10-2)-fold cross-subject validation.
- **Hyperparameter Optimization**: Uses Bayesian Optimization for model tuning to achieve optimal performance in ADHD diagnosis.

## Code and Usage
(Provide setup instructions, library requirements, and step-by-step usage commands here.)

## Contributing
(Include guidelines for contributing to the project, if applicable.)

## License
(Indicate the license under which your code is available, e.g., MIT, GPL.)

## Citation
(Provide citation details for referencing your paper in academic work.)
