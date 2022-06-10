# What is CNN ?

# Areas of application ?
Image classification

# Why CNN for images - Images suffer fromm Curse of dimensionality - Capture the pixels using less number of parameters.


Below are the layers in the CNN :
# 1 - Convolution layer : 
Convolution layer captures the details of the images using padding or striding convolution filters. A convolution filter slides over 
all the pixels of the image taking their dot product.

The use of filter / kernel instead of a fully connected network comes with added benefit of weight sharing and reduction in computational costs.
As we use the same kernel to conolve across different pixels of the image, same weights are reused.

# Padding vs Strided Convolutions
For a n * n image, 
after applying striding convolution using filter of size f * f, the resultant image become n - f + 1, n - f + 1 
after applying padded of p pixels and using filter of size f * f, the resultant image become n + 2p - f + 1, n + 2p - f + 1 
Note : Padding is used to keep the shape of the input data unchanged.

# Why odd size for filter ? 1 * 1, 3 * 3, 5 * 5 , .....
The formula for padding size p = (f-1)/2, where f is the filter matrix shape. 
Now in order to padding size (p) to be a whole number we need f to be odd. This is why it is a convention to use the odd-shaped filter matrix.

# 2 - Pooling layer :
Why Pooling layer - to reduce the complexity further down

The three types of pooling operations are:
Max pooling: The maximum pixel value of the batch is selected - selects the brighter pixels from the image. 
Min pooling: The minimum pixel value of the batch is selected - selects the darker pixels from the image. Gives better result 
for images with white background and black object
Average pooling: The average value of all the pixels in the batch is selected - smooths out the image.
referece: https://medium.com/@bdhuma/which-pooling-method-is-better-maxpooling-vs-minpooling-vs-average-pooling-95fb03f45a9#:~:text=Max%20pooling%3A%20The%20maximum%20pixel,in%20the%20batch%20is%20selected.



