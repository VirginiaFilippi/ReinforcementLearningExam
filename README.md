# RLExam
Repository for the Reinforcement Learning exam

## Installation
These steps are for the installation of the repository on Windows:

1. Clone the repository:

git clone https://github.com/VirginiaFilippi/RLExam.git

2. Create a virtual environment with conda:

conda create -n spinningup python=3.6
conda activate spinningup
conda install -c conda-forge msmpi

3. Clone the repository of spinningup inside of the repository and install the dependencies of spinningup

git clone https://github.com/openai/spinningup.git
cd spinningup
pip install -e .
