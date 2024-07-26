# SPR 2023 (Español)
## Métodos para analizar oscilaciones neuronales y actividad aperiódica en el cerebro ###

Tutoriales y Jupyter Notebooks para analizar oscilaciones neuronales no sinusoidales y actividad aperiódica cerebral.

## Hay dos opciones diferentes para ejecutar estos Notebooks:
### Opción 1: Google Colaboratory (no es necesario instalar Jupyter)

| Tutoriales | Colab Link |
| - | --- |
|  DSP y Simulaciones - Introducción | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/00_dsp_and_sims/dsp_and_sims_00-Introduction.ipynb) |
|  DSP y Simulaciones - Filtros | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/00_dsp_and_sims/dsp_and_sims_01-Filtering.ipynb) |
|  DSP y Simulaciones - Escalas temporales | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/00_dsp_and_sims/dsp_and_sims_02-Timescales.ipynb) |
|  DSP y Simulaciones - Relación Entre Banda de Frecuencia | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/00_dsp_and_sims/dsp_and_sims_03-BandRatios.ipynb) |
|  Parametrización Espectral - Descripción del Modelo | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/01_specparam/specparam_00-ModelDescription.ipynb) |
|  Parametrización Espectral - Algoritmo | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/01_specparam/specparam_01-Algorithm.ipynb) |
|  Parametrización Espectral - Simulación de Datos   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/01_specparam/specparam_02-SimData.ipynb) |
|  Parametrización Espectral - Datos Biológicos   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/01_specparam/specparam_03-RealData.ipynb) |
|  Bycycle - Introducción  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/02_bycycle/bycycle_00-Introduction.ipynb) |
|  Bycycle - Algoritmo  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/02_bycycle/bycycle_01-Algorithm.ipynb) |
|  Bycycle - Datos Biológicos  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/02_bycycle/bycycle_02-RealData.ipynb) |
|  Bycycle - Detección de Bursting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/master/tutorials/02_bycycle/bycycle_03-BurstDetection.ipynb) |

### Opción 2: Ejecutar localmente con tu instalación de Jupyter

```bash
git clone https://github.com/voytekresearch/spr.git
cd spr

pip install -r requirements.txt
jupyter notebook
```