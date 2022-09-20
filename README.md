# ai-env
This repo automates creating environment for AI developement (ML, Vision, NLP, ...)

1. Install Miniconda from [here](https://docs.conda.io/en/main/miniconda.html) and initialize it.

2. Clone this repository.

```git clone https://github.com/SadeghPouriyanZadeh/ai-env.git```

3. Open a terminal with conda base in the ```ai-env``` directory.

4. Create ml environment using conda using PyTorch/TensorFlow.

* PyTorch:

```conda create --name ml --file pytorch_requirements.txt --channel conda-forge --channel anaconda --channel pytorch```

* TensorFlow:

```conda create --name ml --file tensorflow_requirements.txt --channel conda-forge --channel anaconda --channel pytorch```

5. Clone ml environment for each project.

```conda create --name project-env --clone ml```