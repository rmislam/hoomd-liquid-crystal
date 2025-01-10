## Create and activate Conda environment
```
conda create --name <env_name> --file requirements.txt
conda activate <env_name>
```

## Install Conda packages
```
conda install hoomd=5.0.0
conda install gsd
conda install -c conda-forge fresnel
conda install freud
conda install -c conda-forge jupyterlab
```

## Run Jupyter Lab
```
jupyter lab .
```

Open the IPython notebook `HOOMD-2D-Liquid-Crystal.ipynb` and simply run all the cells.
