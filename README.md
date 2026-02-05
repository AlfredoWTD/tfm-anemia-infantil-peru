# tfm-anemia-infantil-peru
Predicción de anemia infantil en Perú mediante aprendizaje supervisado. Análisis de datos ENDES 2015-2024 (130k registros). TFM - Máster en Ciencia de Datos, UNIR.
# Predicción de Anemia Infantil en Perú mediante Aprendizaje Supervisado

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Trabajo de Fin de Máster - Universidad Internacional de La Rioja (UNIR)  
Autor: Alfredo Walter Tinco Domínguez  
Año: 2025

---

## 📋 Descripción del Proyecto

Este repositorio contiene el código y documentación del Trabajo de Fin de Máster 
enfocado en la predicción de anemia infantil en Perú mediante técnicas de 
aprendizaje supervisado.

### Objetivos
- Identificar factores predictores de anemia en niños peruanos de 6-35 meses
- Desarrollar y comparar modelos de clasificación (Random Forest, XGBoost, LightGBM)
- Optimizar el modelo para maximizar recall (prioridad en salud pública)
- Crear un dashboard analítico en Power BI para visualización de resultados

---

## 📊 Datos

**Fuente**: Encuesta Demográfica y de Salud Familiar (ENDES) - INEI  
**Período**: 2015-2024  
**Muestra**: 131,468 registros de niños (6-35 meses)  
**Variables predictoras**: 18 (12 numéricas, 6 categóricas)



### 📥 Descarga de datos ENDES
1. Visitar: https://proyectos.inei.gob.pe/microdatos/
2. Seleccionar **"ENDES"** → años 2015-2024
3. Descargar módulos requeridos (ver [data/README.md](data/README.md))
4. Colocar archivos `.sav` en carpeta `data/raw/`

**Módulos necesarios**: RECH0, RECH1, RECH6, RECH23, REC0111, REC21, REC44

---

## 🛠️ Tecnologías y Herramientas

- **Python 3.8+**: pandas, scikit-learn, LightGBM, XGBoost, imbalanced-learn
- **Power BI Desktop**: Dashboard interactivo
- **SQLite**: Data warehouse para visualización
- **Metodología**: CRISP-DM

---

## 🚀 Reproducibilidad del Proyecto

### 1. Clonar repositorio
```bash
git clone https://github.com/AlfredoWTD/tfm-anemia-infantil-peru.git
cd tfm-anemia-infantil-peru
```



- Instituto Nacional de Estadística e Informática (INEI) - Datos ENDES
- UNIR - Dirección académica
- [Nombre asesor/a] - Tutoría del TFM
