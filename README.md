# DenoisingAutoencoder
Denoising AutoEncoder as Preprocessing for Classification


In this exercise I will use the MNIST Dataset to implement a denoising autoencoder and use it as a preprocessing step for a classification task. I will follow the next steps:

**For the Autoencoder as preprocessing:**
1.   Define the dataloader over data during training phase.
2.   Define the encoder and decoder, using ReLU (hidden layers) and Sigmoid (output layer) as activation functions.
3.   Train the model applying Adam Optimizer and MSE as the loss function.
4.   Finally, I will compare the results using the corrupted image, the reconstructed image and the original image.

**Classification Comparison:**
1.   Using the denoising images I will train a simple classifier and see the results.
2.   Using the original images I will train another simple classifier.
3.   Compare the results of the classification task between the denoising images and the original ones.
