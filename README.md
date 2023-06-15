# Hybrid-Images

Gaussian filtering produces a low-pass (blurred) filtered version of an image. Consequently, the difference between the original and the blurred low-pass filtered 
counterpart results in a high-pass filtered version of the image. 
As defined in the original ACM Siggraph 2006 paper a hybrid image is the sum of a low-pass filtered version of the one image and a high-pass filtered version of a 
second image. There is a free parameter, which can be tuned for each image pair, which controls how much  high frequency to remove from the first image and how much 
low frequency to leave in the second image. This is called the “cutoff-frequency”. 
Considering this, this project combines a pair of images reasonably well to form a hybrid image.
