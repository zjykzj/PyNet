# PyNet

![](./imgs/logo.png)

[![Documentation Status](https://readthedocs.org/projects/zj-pynet/badge/?version=latest)](https://zj-pynet.readthedocs.io/zh_CN/latest/?badge=latest) [![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme) [![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org) [![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

[中文版本（Chinese version）](./README.md)

> Numpy-based deep learning library

Implementation of deep learning based on numpy, modular design guarantees easy implementation of the model, which is suitable for the introduction of junior researchers in deep learning.

## Table of Contents

- [PyNet](#pynet)
  - [Table of Contents](#table-of-contents)
  - [Background](#background)
  - [Badge](#badge)
  - [Install](#install)
  - [Usage](#usage)
  - [CHANGELOG](#changelog)
  - [TODO](#todo)
  - [Maintainers](#maintainers)
  - [Thanks](#thanks)
  - [Contributing](#contributing)
  - [License](#license)

## Background

Systematic learning convolution neural network has been nearly half a year.Using librarys such as pytorch can't understand the implementation in depth. So I plan to complete a deep learning framework from scratch.The initial implementation will refer to the operation of cs231n, and then we will implement it in the form of computational graphs. I hope this project can improve my programming ability and help others at the same time. 

## Badge

If you use PyNet, add the following Badge 

[![pynet](https://img.shields.io/badge/pynet-ok-brightgreen)](https://github.com/zjZSTU/PyNet)

To add in Markdown format, use this code:

```
[![pynet](https://img.shields.io/badge/pynet-ok-brightgreen)](https://github.com/zjZSTU/PyNet)
```

## Install

PyNet need the following prerequisites

* python3.x
* numpy
* opencv3.x

## Usage

Refer to the sample code under the [example](https://github.com/zjZSTU/PyNet/tree/master/examples) folder

Full version reference [releases](https://github.com/zjZSTU/PyNet/releases)

Realized Network Model（Located in [pynet/models](https://github.com/zjZSTU/PyNet/tree/master/pynet/models) folder）：

* 2-Layer Neural Network
* 3-Layer Neural Network
* LeNet-5
* AlexNet
* NIN

Realized Network Layer（Located in [pynet/nn](https://github.com/zjZSTU/PyNet/tree/master/pynet/nn) folder）：

* Convolution Layer (Conv2d)
* Fully-Connected Layer (FC)
* Max-Pooling layer (MaxPool)
* ReLU Layer (ReLU)
* Random Dropout Layer (Dropout/Dropout2d)
* Softmax
* Cross Entropy Loss
* Gloabl Average Pool (GAP)

## CHANGELOG

see the [CHANGELOG](./CHANGELOG.md) on this repository.

## TODO

* Realization of batch normalization
* Realization of Computational Graph

## Maintainers

* zhujian - *Initial work* - [zjZSTU](https://github.com/zjZSTU)

## Thanks

* [cs231n](http://cs231n.github.io/)
* [PyTorch](https://pytorch.org/)

## Contributing

Anyone's participation is welcome! Open an [issue](https://github.com/zjZSTU/PyNet/issues) or submit PRs.

Small note:

* Git submission specifications should be complied with [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.4/)
* If versioned, please conform to the [Semantic Versioning 2.0.0](https://semver.org) specification
* If editing the README, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

[Apache License 2.0](LICENSE) © 2019 zjZSTU
