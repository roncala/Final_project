Final Project using FER2013 Dataset - 7 classes/emotions

Baseline_CNN.py : uses two small convolution blocks to reach a 12 × 12 latent grid without destroying detail.

mobilenet_v3_final-3.py : uses pre trained model MobileNet, with over sampling for minority classes and fine tuning

mobilenet_v5_final.py : uses  pre trained model MobileNet, in only 2 classes from the dataset, also applying fine tuning and
calibrating the models evaluation.
