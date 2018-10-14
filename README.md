# gyanadata-rgbtogreyimage_with-neuralnet

# RGB to GrayScale using Neural Network
## Model Description:


It's a basic Convolutional Neural Network with only one layer of a 1x1x3 kernel which learns the parameters for converting an RGB image to GreyScale.
Loss used is Mean Squared Error
Random RGB pictures have been used to train the model and the training and test set has been synthesized using cv2.
For application of this model, use the function convert(image) that takes in the HxWx3 image and converts it into GreyScale
* Note: cv2 reads file in such a manner that the image is opened in BGR format instead of RGB. Convert the BGR image to RGB explicitly using cv2.
