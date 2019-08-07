Proximal Mean-field for Neural Network Quantization - Code
==========================================================

This code implments the PMF algorithm described in the following paper:

["Proximal Mean-field for Neural Network Quantization"](https://arxiv.org/abs/1812.04353).
Thalaiyasingam Ajanthan, Puneet K. Dokania, Richard Hartley, and Philip H. S. Torr.
ICCV, 2019.

If you're using this code in a publication, please cite our paper.

```
@article{ajanthan2019pmf,
  author       = {Ajanthan, Thalaiyasingam and Dokania, Puneet K. and Hartley, Richard and Torr, Philip H. S.},
  title        = {Proximal Mean-field for Neural Network Quantization},
  journal      = {ICCV},
  year         = {2019}
}
```

This code is for research purposes only.
If you want to use it for commercial purpose please contact us.

Contact: thalaiyasingam.ajanthan at anu.edu.au

Dependencies
------------

[PyTorch](https://pytorch.org/get-started/locally/), tested with PyTorch 1.0, and torchvision 0.2.1 in Python 2.
[numpy](https://numpy.org/)
[pandas](https://pandas.pydata.org/)
[bokeh](https://bokeh.pydata.org/en/latest/)    

How to run the example
----------------------

Example scripts on how to run the code can be found in the _scripts/_ folder. 

```
bash scripts/cifar10-resnet18.bash
```

Acknowledgements
----------------------

[BNN](https://github.com/itayhubara/BinaryNet.pytorch), for some utility functions.
[ResNet/VGG](https://github.com/kuangliu/pytorch-cifar), for model definitions.



