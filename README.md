# LII Congreso Nacional de Psicología CNEIP 2026
## Métodos para Analizar Oscilaciones Neuronales y Actividad Aperiódica

Libretas y tutoriales para analizar oscilaciones neuronales no sinusoidales y actividad aperiódica.

---

## Tienes dos opciones para ejecutar estas libretas:

### Opción 1: Google Colaboratory (no requiere instalación local)

| Tutorial | Enlace a Colab |
| :--- | :--- |
| Procesamiento Digital de Señales (DSP) y Simulaciones - Introducción | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/spanish/tutorials/00_dsp_and_sims/dsp_and_sims_00-Introduction.ipynb) |
| DSP y Simulaciones - Filtrado | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/spanish/tutorials/00_dsp_and_sims/dsp_and_sims_01-Filtering.ipynb) |
| DSP y Simulaciones - Escalas de Tiempo | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/spanish/tutorials/00_dsp_and_sims/dsp_and_sims_02-Timescales.ipynb) |
| DSP y Simulaciones - Ratios de Banda | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/spanish/tutorials/00_dsp_and_sims/dsp_and_sims_03-BandRatios.ipynb) |
| Parametrización Espectral - Descripción del Modelo | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/spanish/tutorials/01_specparam/specparam_00-ModelDescription.ipynb) |
| Parametrización Espectral - Algoritmo | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/spanish/tutorials/01_specparam/specparam_01-Algorithm.ipynb) |
| Parametrización Espectral - Datos Simulados | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/spanish/tutorials/01_specparam/specparam_02-SimData.ipynb) |
| Parametrización Espectral - Datos Reales | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/voytekresearch/spr/blob/spanish/tutorials/01_specparam/specparam_03-RealData.ipynb) |
---

### Opción 2: Ejecución local con Jupyter

Para correr las libretas en tu propia computadora, sigue estos pasos en tu terminal (se recomienda usar Python 3.9):

```bash
# Clonar el repositorio especificando la rama 'spanish'
git clone -b spanish [https://github.com/voytekresearch/spr.git](https://github.com/voytekresearch/spr.git)
cd spr

# Crear un entorno virtual
python3.9 -m venv spr_env
source spr_env/bin/activate

# Actualizar pip e instalar dependencias
pip install --upgrade pip
pip install ipykernel "matplotlib-inline<0.1.7" -r requirements.txt

# Configurar el kernel para Jupyter
python -m ipykernel install --user --name=spr_env --display-name "spr_env"

# Iniciar Jupyter Notebook
jupyter notebook