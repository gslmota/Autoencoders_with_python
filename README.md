# Autoencoders_with_python
This repository contains codes about encoders implemented with python over the MNIST and CIFAR10 datasets.
The implementations are simple neural networks and convolutional networks.
The projects are separated by folders, with the name of the datasets.

# Contents
``` shell
.
├── CIFAR10
│   └── Deep_Autoencoders_base_CIFAR_10.ipynb
├── img
│   ├── enc.png
│   └── enm.png
├── LICENSE
├── MNIST
│   ├── Autoencoders_e_classificação.ipynb
│   ├── Compactação_de_imagens_com_autoencoders.ipynb
│   ├── Compactação_de_imagens_com_Convolutional_Autoencoders.ipynb
│   └── Compactação_de_imagens_com_Deep_Autoencoders.ipynb
├── README.md
└── requirements.txt
```
The **MNIST** folder contains the python codes used in projects.The other folders follow the same pattern.

# Requirements

 * Check the **requirements.txt** file.


# Test

```shell
git clone https://github.com/gslmota/Autoencoders_with_python.git
cd Autoencoders_with_python
pip install -r requirements.txt
```


# Results

### **MNIST**: 
* **Cnn**. This project using simple NN and CNN.

* Epochs 0 / 40 / 100
![!MNIST](https://github.com/gslmota/Autoencoders_with_python/blob/main/img/enm.png)


### **CIFAR10**: 
* **Cnn**. This project using Deep CNN.

* Epochs 0 / 40 / 100
![!CIFAR10](https://github.com/gslmota/Autoencoders_with_python/blob/main/img/enc.png)