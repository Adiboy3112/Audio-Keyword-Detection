# Custom Audio Keyword detection

In this Project we classify audio keywords, for starters we took 2 keywords only for testing, then I have used the audio curration script from Edge Impulse to augment custom recorded keywords such as `hello` and `stop` make a larger training set with bg noise in it with 4800 audio samples of 1 sec uniformly divided among 4 classes
`noise`, `unknown`, `hello`, `stop`. Then I use MFCC's to extract the cepstral coefficients as features for our models and transform it into linear spectral image to which we can feed into a Convolutional Neural Network to classify the image using 1D kernels. Then to reduce the size of kernel output matrix max pool layer
blah blah blah 
will continue tomorrow good night its too late.........
