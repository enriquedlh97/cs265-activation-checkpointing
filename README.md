# CS265-mlsys-project

This repo is the starter code for [Harvard CS265 ML Systems project](http://daslab.seas.harvard.edu/classes/cs265).

## How to start
1. Clone the repo

2. Create your own upstream, and switch your local repo to the new upstream

3. Prepare the software environment
``` bash
conda create -n cs265
conda activate cs265

conda install conda-forge::python=3.12 conda-forge::numpy=2.2.2 pytorch::pytorch=2.5.1 pytorch::pytorch-cuda=12.4 -n cs265
```

4. Run the starter code
``` bash
python starter_code.py
```

5. If you have any questions, feel free to come to the labs and/or share at Ed!

## Useful materials
1. The section recordings

The section slides and recordings can be found at the class webpage: http://daslab.seas.harvard.edu/classes/cs265

2. The Mu2 paper

Sanket Purandare, Abdul Wasay, Animesh Jain, Stratos Idreos:
[μ-TWO: 3× Faster Multi-Model Training with Orchestration and Memory Optimization](https://proceedings.mlsys.org/paper_files/paper/2023/file/a72071d84c001596e97a2c7e1e880559-Paper-mlsys2023.pdf). MLSys 2023

3. The official PyTorch documents

[torch.fx](https://pytorch.org/docs/2.5/fx.html) is particularly relevant to our project.


```bash
curl -sSL https://install.python-poetry.org | python3 -
```

check terminal type
```bash
echo $SHELL
```

If bash, check for profie
```bash
ls -la ~/.bashrc ~/.bash_profile ~/.profile
```
if bash, add poetry to path and reload
```bash
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

use vim and not nano
```bash
echo 'export EDITOR=vim' >> ~/.bashrc
source ~/.bashrc
```

install cuda
```bash
sudo apt update
sudo apt install -y nvidia-driver-535
sudo reboot
```

