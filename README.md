# MultiTaskModel
In this Project, we use no. of grey-scale hand-written numbers and generate new colored training and validation images.
Meanwhile, We use the pixel values of grey-scale image to decide either red-channel values or green-channel values of
image(randomly and set blue-channel values to zero).

Thus generated images train the convolution neural network model (using keras functional API`) with skip connections that gives 2 output: `multiclass digit output` and
`binary class color output`.

The trained model has the 100% accuracy for color and 98% accuracy digit accuracy for validation dataset and 97% digita accuracy for training dataset.

![](image.png)
