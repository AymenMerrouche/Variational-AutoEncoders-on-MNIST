# Variational-AutoEncoders-on-MNIST
Linear Layers based variational auto-encoder on MNIST

## Dataset
MNIST

## You need
- PyTorch
- torchvision
- numpy

# Results
We get the following results with a 2 dimensional latent space :

## Reconstruction and Sampling
Reconstruction and Sampling example :

![Reconstruction and Sampling example with a dimension of the latent sapce equal to 2](./figures/epoch_=_29.png "Epoch = 30")

## Distangling Factors of Variation
Sampling while varying dimensions in latent space :
![Sampling while varying dimensions in latent space](./figures/interpolation_large.png "Epoch = 30")

## Embeddings in latent space
Embeddings in latent space for each class (encoder output on an exmaple of every class) :

![encoder output on an exmaple of every class](./figures/latent_space.png "Epoch = 30")
