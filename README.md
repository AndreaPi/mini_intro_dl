# A mini-intro to Deep Learning in Python 

A short introduction to Deep Learning, its history and application in Computer Vision. Uses Keras.

## Hardware requirements
To train the ResNet50 model from scratch on [Imagenette](https://github.com/fastai/imagenette), a small subset of the ImageNet dataset, you will need a GPU. You can run the rest of the notebook without it. 


## Software requirements
* Keras 2.3.0 or higher (but with just a couple minor modifications, the code runs with Keras 2.2.4 or higher).
* Python 3.6 or higher.

### Installation
I recommend installing the requirements in a virtual enviroment, or running in a Docker container with Linux.
If you plan to run the whole notebook, including the **Training** part:
```
pip install -r requirements_gpu.txt
```

If you're ok with skipping the **Training** part at the end of the notebook:

```
pip install -r requirements.txt
```

That's all. Have fun, and let me know if you liked it!