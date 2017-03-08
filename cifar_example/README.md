# CIFAR example
The first two notebooks simply download the data and train/evaluate the model. These are simply run using Batch Shipyard
The final notebook orchestrates everything, please start [here](train_on_azure_batch_shipyard.ipynb). 

* [Prepare CIFAR Data](process_cifar_data.ipynb) Downloads the data and formats is appropriately for the network
* [Train CNN Model](cntk_cifar10.ipynb) Trains and evaluates the model
* [Train model on Batch Shipyard](train_on_azure_batch_shipyard.ipynb) Creates the Docker image and runs it on a single GPU node using Azure Batch Shipyard

