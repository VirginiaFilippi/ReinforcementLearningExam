# RLExam

This is the repository for the Reinforcement Learning exam @UniVR, academic year 2023-2024.

Authors: Virginia Filippi and Martina Toffoli

The repository contains the simulations code and results obtained by training the **Deep Deterministic Policy Gradient (DDPG)** algorithm from SpinningUp OpenAI code.

The code was tested on 3 continuous environments: 
- Mountain Car,
- Pendulum, 
- Lunar Lander.

The results of the experiments and the performance plots are contained in the folder `experiments`.


## Installation
These steps are for the installation of the repository on Windows, that works for me.

> **_NOTE:_**  Please, pay attention to the versions of the `spinningup` library packages because the library is not updated since 2020.

1. Clone the repository:

```
git clone https://github.com/VirginiaFilippi/RLExam.git
```

2. Create a virtual environment with conda:

```
conda create -n spinningup python=3.6
conda activate spinningup
conda install -c conda-forge msmpi
```

3. Clone the repository of spinningup inside of the repository and install the dependencies of spinningup

```
git clone https://github.com/openai/spinningup.git
cd spinningup
pip install -e .
```


## Code
Follow the code in the `main.ipynb`, that contains the code to run the training loops for PyTorch and Tensorflow versions of DDPG, and the code of performance plotting.