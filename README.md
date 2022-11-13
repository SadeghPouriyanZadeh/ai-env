# ai-env
This repo guides you to create an environment for AI developement

1. Install Miniconda from [here](https://docs.conda.io/en/main/miniconda.html) and initialize it.

2. Clone this repository.

```git clone https://github.com/SadeghPouriyanZadeh/ai-env.git```

3. Open a terminal with conda base in the ```ai-env``` directory.

4. Create ml environment using conda.

```conda create --name ml --file requirements.txt --channel conda-forge --channel anaconda --channel pytorch```

5. Clone ml environment for each project.

```conda create --name project-env --clone ml```

6. for using pytorch go to its installation page from [here](https://pytorch.org/get-started/locally/)
