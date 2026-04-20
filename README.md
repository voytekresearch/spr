# SPR 2023
## Pre-Conference Workshop #1: Methods for Analyzing Neural Oscillations and Aperiodic Activity ###

Notebooks and tutorials for analyzing nonsinusoidal neural oscillations and aperiodic activity.

## You have two options for running these notebooks:
### Option 1: Google Colaboratory (no Jupyter installation necessary)

| Tutorial | Colab Link |
| - | --- |
|  DSP and Simulations - Introduction | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/00_dsp_and_sims/dsp_and_sims_00-Introduction.ipynb) |
|  DSP and Simulations - Filtering | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/00_dsp_and_sims/dsp_and_sims_01-Filtering.ipynb) |
|  DSP and Simulations - Timescales | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/00_dsp_and_sims/dsp_and_sims_02-Timescales.ipynb) |
|  DSP and Simulations - Band Ratios | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/00_dsp_and_sims/dsp_and_sims_03-BandRatios.ipynb) |
|  Spectral Parameterization - Model Description  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/01_specparam/specparam_00-ModelDescription.ipynb) |
|  Spectral Parameterization - Algorithm   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/01_specparam/specparam_01-Algorithm.ipynb) |
|  Spectral Parameterization - Simulated Data   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/01_specparam/specparam_02-SimData.ipynb) |
|  Spectral Parameterization - Real Data   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/01_specparam/specparam_03-RealData.ipynb) |
|  Bycycle - Introduction  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/02_bycycle/bycycle_00-Introduction.ipynb) |
|  Bycycle - Algorithm  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/02_bycycle/bycycle_01-Algorithm.ipynb) |
|  Bycycle - Real Data  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/02_bycycle/bycycle_02-RealData.ipynb) |
|  Bycycle - Burst Detection | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/02_bycycle/bycycle_03-BurstDetection.ipynb) |

### Option 2: Run locally with your own Jupyter installation

```bash
git clone https://github.com/voytekresearch/spr.git
cd spr

# python3.11 -m venv spr_env

# source spr_env/bin/activate

# pip install --upgrade pip setuptools wheel

# pip install -r requirements.txt

# pip install ipykernel
# python -m ipykernel install --user --name=spr_env --display-name "spr_env"

# pip install --upgrade "matplotlib==3.6.0" --force-reinstall

# pip install "numpy==1.25.2"
# pip install "matplotlib-inline<0.1.7"


python3.9 -m venv spr_env
source spr_env/bin/activate

pip install --upgrade pip
pip install ipykernel "matplotlib-inline<0.1.7" -r requirements.txt

python -m ipykernel install --user --name=spr_env --display-name "spr_env"
jupyter notebook
```