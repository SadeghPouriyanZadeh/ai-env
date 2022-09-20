# ai-env
this repo tries to automate creating a development environment for developing artificial intelligence.

1. install Miniconda from [here](https://docs.conda.io/en/main/miniconda.html) and initialize it

2. clone this repository

```git clone https://github.com/SadeghPouriyanZadeh/ai-env.git```

3. open a terminal with conda base in the ```ai-env``` directory

4. create ml environment using conda

```conda create --name ml --file essential_packages.txt --channel conda-forge --channel anaconda --channel pytorch```