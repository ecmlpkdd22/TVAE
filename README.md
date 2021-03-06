# TVAE for Image Reconstruction
Transformer-based Variational AutoEncoder - Keras implementation. 
The TVAE leverages the shared attention layers of the Transformer to maximize the contextual information, and converts an input to the corresponding training distribution without increasing model complexity.

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

### Training

- Use the ```config.yml``` configuration file to train a TVAE with desired encoder and decoder network parameters, training parameters (e.g.: learning rate) and the data set (MNIST, Fashion-MNIST or SVHN). Then run the main script ```TVAE.py```.
- For the CelebA, firstly, download the [celebA dataset align](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) into the ![dataset](dataset/) directory. After installing all the third-party [packages required](https://keras.io/examples/generative/dcgan_overriding_train_step/),  we can run the model by:


```bash
python TVAE.py
```


