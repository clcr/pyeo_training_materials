# pyeo_training_materials
A collection of training materials for Pyeo

## Installation

To run through these training materials, you will need the following prerequisites:
- Git
- Anaconda/Miniconda

To install Pyeo and the training materials, put the following commands into Bash (Linux/Mac) or the Anaconda **Console** (Windows)

```bash
git clone https://github.com/clcr/pyeo.git
git clone https://github.com/clcr/pyeo_training_materials.git
cd pyeo
conda env create --file environment.yml --name pyeo_env
conda activate pyeo_env
python -m pip install -e . -vv
```

To use this notebook:

```bash
conda activate pyeo_env
jupyter notebook pyeo_training_materials
```

And start from exercise_1.ipynb
