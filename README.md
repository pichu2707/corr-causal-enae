# Ejemplos de Correlación e Inferencia Causal en Python

Este repositorio contiene una serie de códigos de ejemplo diseñados para demostrar:

- **Medidas de Correlación:**
  - **Covarianza:** Para evaluar cómo varían conjuntamente dos variables.
  - **Correlación de Pearson:** Para medir la relación lineal entre dos variables cuantitativas.
  - **Correlación de Spearman:** Para identificar relaciones monótonas (no necesariamente lineales) entre variables, especialmente útil cuando se tienen datos ordinales o se desea mitigar el impacto de valores atípicos.

- **Modelo Causal e Inferencia Causal:**
  - **Diferencias en Diferencias (DiD):** Un ejemplo práctico donde se simulan datos para evaluar el efecto de una intervención (por ejemplo, una campaña publicitaria en marketing) comparando un grupo de tratamiento y uno de control en dos momentos (antes y después de la intervención).

## Requisitos y Entorno

Los ejemplos están implementados en **Python** y se han probado utilizando **Python 3.8** (la versión puede ser adaptada según tus necesidades). Algunas de las librerías utilizadas incluyen:

- `numpy`
- `pandas`
- `statsmodels`
- `scipy`

Asegúrate de instalar las dependencias necesarias utilizando, por ejemplo, `pip`:

```bash
pip install numpy pandas statsmodels scipy

````

Si lo que vas a utilizar es Colab no necesitas instalar nada.
