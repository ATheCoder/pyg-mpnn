### On Macbook M1

```
conda create --prefix ./env python=3.8
conda activate ./env
conda install -c pytorch pytorch
conda install -c conda-forge jupyter jupyterlab
pip install torch-scatter torch-sparse torch-cluster torch-spline-conv torch-geometric -f https://data.pyg.org/whl/torch-1.12.0+cpu.html
```