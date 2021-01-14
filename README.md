# Image_Colorization

In this project, the model is trained to color grayscale images based on CNN. Model
comprises of VGG16(encoder) and custom made decoder. LAB color space is used. L
channel is fed as input to autoencoder and A,B channels are predicted by the model.
L(input) and A,B(output) channels are combined to produce a colorimage.
