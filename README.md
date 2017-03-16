# Using Azure Batch Shipyard to train Deep Learning Models
This repo contains a number of example notebooks to run Deep Learning models on GPUs using Azure Batch Shipyard.

* [CIFAR Example](cifar_example) Creates a simple 3 layer convolution network which is then trained and evaluated against the CIFAR10 dataset. 

** WARNING
Azure Batch and some of the Azure components are in the process of being updated. This breaks some of the dependencies of the 2.5.4 release of Batch Shipyard. 
There is a temporary branch called [update](https://github.com/msalvaris/batch_shipyard_notebooks/tree/update) that you can use during the transition. 
As soon as the new version of Batch Shipyard is released the notebooks will be updated.
**