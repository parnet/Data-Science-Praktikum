# Install the environment

use Anaconda, conda or miniconda to create a virtual environment in which every modul will be installed. Git is also needed to clone the aix360 repository
The installation process can be different on every machine. For us it was neccessary to install some module before installing aix or interpret 

```
conda create --name aix360 python=3.6
conda activate aix360
conda install -c conda-forge pytorch
conda install -c omnia quadprog
conda install -c conda-forge cvxpy
conda install -c conda-forge shap
conda install -c conda-forge tensorflow

git clone https://github.com/IBM/AIX360
pip install -e .

pip install interpret
```

### launch notebook
the notebooks are in the subfolder nbsrc

