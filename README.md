# Terrain-Identification-System

## Overview
The natural walking ability of humans is optimized for energy efficiency, stability, adaptability to different environments, and resilience. Unfortunately, lower limb amputations impair this capability, leaving individuals reliant on prosthetic devices to regain basic locomotion functions. Our project focuses on enhancing lower-limb robotic prosthetics with context awareness to improve comfort and safety for amputees. Specifically, we seek to create a terrain recognition system that utilizes data from inertial measurement units (IMU) attached to the lower limb. While current systems incorporate both visual and inertial sensors for this purpose, our objective is to determine the feasibility of identifying terrain using only inertial data. This capability would enable dynamic adjustments in the prosthetic's control mechanisms based on the terrain it encounters.

## Objective
The project involves a classification task aimed at distinguishing various terrains using time series data. We plan to develop and train a neural network with the provided data to accurately identify the terrain represented by new, unseen data. The F1 score will serve as the metric for evaluating the performance of our model.

## Data Explanation
"_x" files: These files include measurements from the xyz accelerometers and xyz gyroscopes attached to the lower limb.

"_x_time" files: These files record the timestamps corresponding to the accelerometer and gyroscope data, with a sampling rate of 40 Hz and units in seconds.

"_y" files: These files contain the terrain labels, where (0) represents standing or walking on solid ground, (1) signifies descending stairs, (2) ascending stairs, and (3) walking on grass.

"_y_time" files: These files provide the timestamps for the terrain labels, with a 10 Hz sampling rate and units in seconds.
