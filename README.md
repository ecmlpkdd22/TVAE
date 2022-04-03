# TVAE for Image Reconstruction
Transformer-based Variational AutoEncoder - Keras implementation on MNISTt, Fashion-MNIST, SVHN, and CelebA datasets

## Usage

**Clone this repository to local**

```python
https://github.com/ecmlpkdd22/TVAE.git

cd TVAE
```

## Dependencies and architecture

- 1 GPU
- keras
- tensorflow
- numpy, matplotlib, scipy
- 2 transformer layers 
- encoder and decoder - both have the same architecture


### MNIST

##### ![src/mnist_train.py](src/mnist_train.py)
- it trains TVAE based on the hyperparameters defined in ![src/mnist_params.py](src/mnist_params.py)
- after training, the model is saved in the ![models](models/) directory and can be used to generate new images


### Fashion-MNIST

##### ![src/f_mnist_train.py](src/f_mnist_train.py)
- it trains TVAE based on the hyperparameters defined in ![src/f_mnist_params.py](src/f_mnist_params.py)


### SVHN

##### ![src/svhn_train.py](src/svhn_train.py)
- it trains TVAE based on the hyperparameters defined in ![src/svhn_params.py](src/svhn_params.py)


### CelebA

##### ![src/celeba_train.py](src/celeba_train.py)
- it trains TVAE based on the hyperparameters defined in ![src/celeba_params.py](src/celeba_params.py)



