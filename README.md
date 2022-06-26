

## Basic classes:

* EENetClass.py - Networks of EE-Net
* EENet.py - Class of EE-Net
* EENet_run.py  - Run proposed algorithm 


* Neural_epsilon.py - fully-connected neural network with epsilon-greedy exploration strategy
* NeuralTS.py - Neural thompson sampling  [Zhang et al. 2020]
* NeuralUCB.py - NeuralUCB [Zhou et al. 2020]
* KernelUCB.py - KernelUCB [Valko et al., 2013a]
* LinUCB.py - LinUCB [Li et al., 2010]
* packages.py - all the needed packages
* load_data.py - load the datasets


## Run:
run EE-Net on Mnist
```
python EENet_run.py     
```
run baselines with default setting on Mnist

```
python baselines_run.py
```

# Prerequisites: 

python 3.8.8

CUDA 11.2

torch 1.9.0

torchvision 0.10.0

sklearn 0.24.1

numpy 1.20.1

scipy 1.6.2

pandas 1.2.4



# EE-Net

@inproceedings{ban2022eenet,

title={{EE}-Net: Exploitation-Exploration Neural Networks in Contextual Bandits},

author={Yikun Ban and Yuchen Yan and Arindam Banerjee and Jingrui He},

booktitle={International Conference on Learning Representations},

year={2022}
}

