## Kaggle > Video Game Sales
https://www.kaggle.com/gregorut/videogamesales

### Using Conda for Jupyter Notebook on Chromebook Linux
Install Instructions
https://alex.miller.im/posts/data-science-chromebook-pixelbook-jupyter-python-r/

<code>source /opt/miniconda3/bin/activate
conda create --name conda_env
conda activate conda_env
conda config --add channels conda-forge
</code>

open your ~/.bashrc file
<code>
# Get conda running in the base environment, activate sub-environment
source /opt/miniconda3/bin/activate
conda activate conda_env
export XDG_RUNTIME_DIR=""
</code>

Installing Jupyter
<code>
conda install jupyter
jupyter notebook --generate-config
</code>

Launch
<code>
jupyter notebook
</code>