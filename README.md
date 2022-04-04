# TVAE for Image Reconstruction
Transformer-based Variational AutoEncoder - Keras implementation on MNISTt, Fashion-MNIST, SVHN, and CelebA datasets

## Dependencies

- 1 GPU
- keras
- tensorflow
- numpy, matplotlib, scipy 

## Usage

**Clone this repository to local**

```python
git clone https://github.com/ecmlpkdd22/TVAE.git

cd TVAE

pip install -r requirements.txt
```

### MNIST, Fashion-MNIST, CVHN

Use the ```config.yml``` configuration file to train a TVAE with desired encoder and decoder network parameters, training parameters (e.g.: learning rate) and the data set (MNIST, Fashion-MNIST or SVHN). Then run the main script ```TVAE.py``` as follows:

```bash
python TVAE.py
```


### CelebA

Firstly, download the [celebA dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) into the ![dataset](dataset/) directory. After installing all the third-party packages required,  we can run the model by:

```python
python TVAE.py
```



