# DigitClassification
Automatic classification of handwritten digits

This project explores methods for classifying handwritten digits from the MNIST data set as given in a long-term, no-prize Kaggle competition. Hand written digits are digitized as 8-bit grayscale images, 28x28 pixels. Each image is therefore represented as a 784-element vector of integers, each in the range 0-255. The data set contains 42,000 images. So, while the number of images is relatively small, the dimensionality is relatively high.

The goal was to test a variety of classifiers alone and combined with dimensionality reduction. The general strategy was to first test a variety of classifiers, then test classifiers with dimensionality reduction, and then choose the final model and make final refinements. 
