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

![Reconstruction and Sampling example with a dimension of the latent sapce equal to 2](https://github.com/AymenMerrouche/Variational-AutoEncoders-on-MNIST/blob/master/figures/epoch_=_29.png)

## Distangling Factors of Variation
Sampling while varying dimensions in latent space :
![Sampling while varying dimensions in latent space](https://github.com/AymenMerrouche/Variational-AutoEncoders-on-MNIST/figures/blob/masterinterpolation_large.png.png)

## Embeddings in latent space
Embeddings in latent space for each class (encoder output on an exmaple of every class) :

![encoder output on an exmaple of every class](https://github.com/AymenMerrouche/Variational-AutoEncoders-on-MNIST/blob/master/figures/latent_space.png)
