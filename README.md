![EathCODE](https://esa-earthcode.github.io/documentation/img/EarthCODE_kv_transparent.png)

EarthCODE (https://earthcode.esa.int/) proactively promotes open science and innovation by providing a federated ecosystem of FAIR and Open Science tools and platforms. EarthCODE integrates EO (Earth Observation) cloud-native platforms for big data analytics, through a federated ecosystem. It enables scalable data management, access, processing, and visualization of datasets as well as reusable data products and workflows.


### Setup

1. git clone the pangeo_earthcode repository.
```bash
git clone https://github.com/u3ks/pangeo_earthcode
```
2. Install the required software environment with Conda. If you do not have Conda, install it by following these instructions (see [here](https://docs.conda.io/en/latest/miniconda.html)). Then create the environment, this can take a few minutes.
```bash
conda env create -n pangeo -f pangeo_earthcode/pangeo_earthcode.yml
```
3. Launch a Jupyterlab notebook server from this environment.
```bash
conda activate pangeo
jupyter lab
```
4. Open a web browser and connect to the Jupyterlab provided URL (you should see it in the jupyter lab command outputs), something like: http://localhost:8888/lab?token=42fac6733c6854578b981bca3abf5152.
5. Navigate to pangeo_on_EarthCODE using the file browser on the left side of the Jupyterlab screen.

