# ai-env
This repo guides you to create an environment for AI developement

## Machine Learning environment

1. Install Miniconda from [here](https://docs.conda.io/en/main/miniconda.html).

2. Clone this repository.

```git clone https://github.com/SadeghPouriyanZadeh/ai-env.git```

3. Open a terminal with conda "base" environment activated in the ```ai-env``` directory.

```conda activate base```

4. Create "ml" environment using "ml_requirements.txt" file.

```conda create --name ml --file ml_requirements.txt --channel conda-forge --channel anaconda --channel pytorch```

5. Clone "ml" environment for each project.

```conda create --name newenv --clone ml```

## Deep Learning Environment

1. Create a new conda environment e.g. "torch" and activate it:

```conda create --name torch```

```conda activate torch```

2. Go to PyTorch installation page from [here](https://pytorch.org/get-started/locally/).

3. Choose your "OS", "Package", and "Compute Platform" and copy the installation command.

for example:

This is for test

```conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia```

4. Then install other recommended packages using "torch_requirements" file.

```conda install --file torch_requirements.txt ```
