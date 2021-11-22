# -Deep-Convolutional-AutoEncoders
1- The encoder and decoder should include more convolution, pooling, upsampling layers. In other words, a more deeper netwok is required.

2- A separate decoder model should be built in addition to the complete autoencoder and the encoder model.

3- Randomly select K images from the test set (K is a parameter that could be changed) and follow the below procedure:
Pass the image to the encoder model to get its code then pass the code to the decoder model to reconstruct the decoded image.
Visualize the original image, its code, and its decoded image
