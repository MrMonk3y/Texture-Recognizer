# Texture-Recognizer

An attempt to recognize textures with a fully convolutional network. The Describable Textures dataset is used for this purpose. The dtd_laoder_color_patches.py grabs the labels and images and reorganizes them. This grabber was written by Prof. Dr. ThomAS Koller (HSLU), not me!

# Performance

Currently validation loss is stuck. The loss keeps decreasing but I stop after 15 epochs so that it won't overfit. Validation accuracy of almost 24% sounds bad in the first place.  Since the model predicts each pixel this is not as bad as first expected. Overall the model is able to predict at least large junks correctly. 

# TODO

- use valid not same
- more generalization
- use residuals