# SBL_AIMC2022
Supplementary materials for AIMC 2022 submission - Synthesis by Layering: Learning a Variational Space of Drum Sounds

## interpolation

This folder contains examples of interpolation between two reconstructions. The interpolation is carried out linearly.

#### interpolation_x.wav
these files are structured as follows:
- sample 1 -> sample 2 (pause)
- sample 1 -> interpolation 1 -> interpolation 2 -> interpolation 3 -> sample 2

#### interpolation_x.png
Contains a visual summary of the interpolation, including the weights at each interpolation point, the waveforms, and a graphic of the weights through the interpolation.

## reconstruction

This folder contains examples of the model's reconstructive capabilities.

#### x_original.wav
- The original input to the system
#### x_reconstruction.wav
- The system's reconstruction of input x
#### x_reconstruction_weights.png
- Contains a bar chart of the weights used to create x_reconstruction.wav

## PCA Latent Space Interaction

This video is a screengrab of a brief demo of our preliminary prototype. We will make the refined product available for download upon publication. This video demonstrates the effects of varying the latent space along a few of its principal components for one particular sample.
