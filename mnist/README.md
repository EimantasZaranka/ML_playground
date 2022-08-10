# MNIST handwritten numbers set

Project purpose was to create a CNN model and try out contrastive learning that was suggested by svpino on twitter. Used his suggested model architecture and loss/accuracy metric. One thing that I changed was instead of dataset in numpy arrays I used TensorFlow Dataset type.

## Few things I could improve on:

1. Tryout different loss metrics.

2. Try to fix model itself because training accuracy was very low (~.5) meanwhile validation and test sets accuracy was quite high (~.93). 

3. Also in the future could be a good idea to create flask web app and run both models in it where user could draw its own numbers and make model predict on it.

## Resources:

1. https://deepnote.com/@svpino/Contrastive-Learning-7a0ec6e4-6a1d-43c7-9d30-aad8ad367334

2. https://www.tensorflow.org/api_docs/python/tf/data/Dataset

## Outputs:

