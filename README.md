# S3N

This repository contains supporting code for our paper [Anomaly Detection in Video Games](https://github.com/BenedictWilkinsAI/S3N). All of the models used in experiments can be found [here](https://www.kaggle.com/benedictwilkinsai/s3n-pretrained-models) along with an **interactive demonstration** (does not require dependancies and is run online). Models are written in [pytorch](https://pytorch.org/).

The `atari-anomaly.ipynb` file is the main file used to train and visualise some aspects of the models.

This repo requires some github dependancies, to avoid backward compatibility issues it is best to use the particular commits given.
For convenience the install script `install.sh` will install all of the correct dependancies, navigate to an empty directory and create a python virtual environment before running the script - `sudo ./install.sh`. 

* **pyworld**
```
git clone -n git@github.com:BenedictWilkinsAI/pyworld-rl.git
git checkout -b <branch> a15675e9b8fa333312e73e751bb737fd4649d3b5
```
* **anomapy**
```
git clone -n git@github.com:BenedictWilkinsAI/anomapy.git
git checkout -b <branch> 11f02ca42c375fc9c39875ba072541c1d8bf9bea
```
* **dataset**
```
git clone -n git@github.com:BenedictWilkinsAI/pydatasets.git
git checkout -b <branch> a9a6fe479361844b57fe662768a6489353ac86b8
```



## Atari Anomaly Dataset (AAD)

Our dataset (AAD) was used to evaluate the performance of S3N, the dataset and more information can be found [here](https://www.kaggle.com/benedictwilkinsai/atari-anomaly-dataset-aad).
