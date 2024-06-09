# generative adversarial network(GAN) using MNIST hand written dataset
The MNIST database is available at http://yann.lecun.com/exdb/mnist/

The MNIST database is a dataset of handwritten digits. It has 60,000 training samples, and 10,000 test samples. Each image is represented by 28x28 pixels, each containing a value 0 - 255 with its grayscale value.

**The Discriminator architecture**
The discriminator is going to be a typical linear classifier.
The activation function we will be using is Leaky ReLu.

**The Generator architecture**
The generator uses latent samples to make fake images. These latent samples are vectors which are mapped to the fake images.
The activation function for all the layers remains the same except we will be using Tanh at the output.

**Samples generated by the generator**
At the start
photo

Overtime
git
This way the generator starts out with noisy images and learns over time.
**Conclusions**