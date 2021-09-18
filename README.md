# NeuralStyleTransfer

Digital Image Processing: The field of digital image processing refers to processing digital images by means of a digital
computer. There is no general agreement among authors regarding where image processing
stops and other related areas, such as image analysis and computer vision, start. Sometimes a
distinction is made by defining image processing as a discipline in which both the input and
output of a process are images. Deep learning methods use data to train neural network
algorithms to do a variety of machine learning tasks. Convolutional neural networks in specific
are deep learning algorithms that are particularly powerful for analysis of images.

Neural style transfer is an optimization technique used to take three images, a content image,
a style reference image (such as an artwork by a famous painter), and the input image you want
to style — and blend them together such that the input image is transformed to look like the
content image, but “painted” in the style of the style image.
The principle of neural style transfer is to define two distance functions, one that describes how
different the content of two images are, Lcontent, and one that describes the difference between
the two images in terms of their style, Lstyle. Then, given three images, a desired style image,
a desired content image, and the input image (initialized with the content image), we try to
transform the input image to minimize the content distance with the content image and its style
distance with the style image.
In Neural Style Transfer we have two images- style and content. We need to copy the style from
the style image and apply it to the content image. By, style we basically mean, the patterns, the
brushstrokes, etc.
In summary, we’ll take the base input image, a content image that we want to match, and the
style image that we want to match. We’ll transform the base input image by minimizing the
content and style distances (losses) with backpropagation, creating an image that matches the
content of the content image and the style of the style image.


