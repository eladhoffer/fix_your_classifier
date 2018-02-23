# Fix Your Classifier

PyTorch implementation of the fixed classifier described in ["Fix your classifier: the marginal value of training the last weight layer"](https://openreview.net/forum?id=ryIn8pg0W) (ICLR-2018) by Elad Hoffer, Itay Hubara and Daniel Soudry.

This repository holds both random orthogonal classifier, and Hadamard classifier. They can be used to replace any ``nn.Linear`` module normally used for classification. 
```
@inproceedings{
hoffer2018fix,
title={Fix your classifier: the marginal value of training the last weight layer},
author={Elad Hoffer and Itay Hubara and Daniel Soudry},
booktitle={International Conference on Learning Representations},
year={2018},
url={https://openreview.net/forum?id=S1Dh8Tg0-},
}
```
