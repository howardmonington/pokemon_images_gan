# Pokemon Images Autoencoder and GAN

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is explore autoencoders and GANs using the pokemon images dataset. The dataset was small, containing only 819 images. I was able to successfully train an autoencoder to remove gaussian noise from images. From there, I attempted to build a GAN to generate new pokemon images. The GAN did not produce intelligent results, but I learned a lot about building GANs while making it.

### Methods Used
* Deep Learning
* Image Visualization
* Autoencoders
* Neural Networks
* GANs

### Technologies
* Python
* Jupyter
* Pandas, numpy
* Matplotlib
* TensorFlow
* Keras
* Python Imaging Library (PIL)


## Project Description
An autoencoder is a type of NN which is used to learn efficient representations for a set of data by ignoring the noise. It works by feeding the data through successively smaller layers until it reaches a bottleneck, which is the compressed representation of the input data. From there, the decoder learns how to reconstruct the data from the compressed representation. To do that, the NN needs to learn only the most important features and ignore noise. This makes it useful for removing noise from images. In this project, I was successfully able to build an autoencoder to remove gaussian noise from images. The output of the autoencoder was more blurry though, as a result of being compressed.

A Generative Adversarial Network (GAN) consists of two neural networks: a generator and a discrimator. In this project, the task of the generator is to create convincing fake images of pokemon while the discriminator attempts to distinguish between the real and fake pokemon images. The idea behind this is that the generator will eventually learn to create very convincing pokemon images that look like they could be real pokemon. In this project, I was unsuccessful at building a GAN to do this, but I learned a lot about GANs along the way.

### Dataset Location
The Raw Data can be found [here](https://www.kaggle.com/kvpratama/pokemon-images-dataset)

## Featured Notebooks/Analysis/Deliverables
* [Notebook](https://github.com/lukemonington/pokemon_images_gan/blob/main/Pokemon%20Autoencoder.ipynb)


## Contributing Members

**[Luke Monington](https://github.com/lukemonington)**

## Contact
* I can be reached at lukemonington@aol.com.
