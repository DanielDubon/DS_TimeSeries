# Laboratorio 01 - Series de Tiempo

## Universidad del Valle de Guatemala  
**Facultad de Ingeniería**  
**Departamento de Ciencias de la Computación**  
**Data Science – Semestre II, 2025**

---

## Proyecto: Análisis y Pronóstico de Importación y Consumo de Combustibles

Este repositorio contiene el desarrollo completo del **Laboratorio 01 - Series de Tiempo**, donde se analiza y modela el comportamiento histórico de consumo e importación de combustibles (Gasolina Superior, Gasolina Regular y Diésel) en Guatemala. 

El proyecto aborda tanto el análisis exploratorio como el modelado predictivo mediante algoritmos **ARIMA** y **Prophet**.

---

## Integrantes del Grupo

- **Daniel Dubon** — 22233  
- **Bianca Calderón** — 22272  
- **Hansel López** — 19026  

---

## Descripción General

Se trabajó con los datos de:

- **Consumo nacional de combustibles:** 2000 a 2025 (último dato disponible).
- **Importación nacional de combustibles:** 2001 a 2025 (último dato disponible).

### Combustibles considerados:

- Gasolina Superior  
- Gasolina Regular  
- Diésel (alto y ultra bajo azufre, consolidado)

Cada variable fue analizada mediante una serie de tiempo univariante.

---

## Contenido del Proyecto

- 📊 **Análisis exploratorio**: 
  - Visualización de tendencias, estacionalidades, efectos de pandemia.
  - Descomposición de las series.
  - Evaluación de estacionariedad (gráfico ACF, prueba Dickey–Fuller).
  
- ⚙️ **Modelado predictivo**:
  - Modelos ARIMA seleccionados mediante AIC.
  - Modelos Prophet ajustados y comparados.
  - Predicción de los próximos 12 meses para cada serie.

- 📈 **Comparación de modelos**:
  - Comparativa de desempeño entre ARIMA y Prophet.
  - Discusión de resultados en el contexto histórico.

---

## Archivos Incluidos

- Notebooks:
  - `RegularNotebook.ipynb`
  - `SuperNotebook.ipynb`
  - `DieselNotebook.ipynb`

- Datos:
  - `importacion.csv`
  - `importacion2025.csv`
  - `consumo.csv`

- Documentación:
  - Libro de códigos colaborativo (Google Docs).

---

## Instrucciones de Ejecución

1. Clonar el repositorio:
    ```bash
    git clone https://github.com/DanielDubon/DS_TimeSeries.git
    ```
2. Instalar las dependencias necesarias:
    ```bash
    pip install -r requirements.txt
    ```
3. Abrir el notebook deseado en Jupyter o VSCode:
    ```bash
    jupyter notebook RegularNotebook.ipynb
    ```
