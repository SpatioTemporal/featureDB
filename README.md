# featureDB

jupyter
hdf5
matplotlib


## Zero-To examples

### Make new Conda environment
```bash
conda create --name ccl python=3.9
conda activate ccl 
conda install -c conda-forge mamba
```


### Install packages
```bash
mamba install -c conda-forge jupyterlab
mamba install -c conda-forge matplotlib
mamba install -c conda-forge pandas
mamba install -c conda-forge dask['distributed']
mamba install -c conda-forge ipympl
#mamba install -c conda-forge nodejs
#mamba install -c conda-forge proj4 
mamba install -c conda-forge basemap
mamba install -c conda-forge netCDF4
mamba install -c conda-forge pip

pip install connected-components-3d
pip install pyhdf
pip install pystare
pip install starepandas

```


## Register Kernel
```bash
conda install -c conda-forge  ipykernel
python -m ipykernel install --user --name=ccl
```
