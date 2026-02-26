# ProyectoForense

Generación de datos sintéticos y entrenamiento aplicando Inteligencia Artificial Explicable (XAI) para la detección, análisis forense y evidencia legal de incidentes de ciberseguridad.

---

## Descripción

Este repositorio contiene la implementación desarrollada en el Proyecto Fin de Máster (PFM) cuyo objetivo es diseñar y validar un sistema de detección de intrusiones que cumpla requisitos técnicos y forenses.

El sistema integra:

* Generación de datos sintéticos
* Modelos de detección binaria
* Evaluación mediante escenarios TSTR
* Explicabilidad mediante SHAP
* Integración en un flujo forense reproducible

El enfoque prioriza la **reproducibilidad**, **trazabilidad** y **validez forense** de los resultados.

---

## Estructura del repositorio

```text
ProyectoForense/
├── Dataset-Full/       # Código fuente de creación de datasets limpios
├── Dataset-Sintetico   # Código fuente de creación de datasets sinteticos
├── Datasets/           # Ficheros JSON con el resultado de las variables
├── RestoCodigo/        # Código fuente para creación de tablas y ficguras
├── Tablas_Figuras/     # Figuras y tablas en formato vectorial
└── README.md

```

> La estructura puede evolucionar ligeramente durante el desarrollo.

---

## Requisitos

* Python 3.9 o superior
* pip

Instalación de dependencias:

```bash
pip install -r requirements.txt
```

---

## Flujo general de ejecución

El pipeline experimental sigue las siguientes fases:

1. Preparación y limpieza de datasets
2. Generación de datos sintéticos mediante SDV
3. Entrenamiento del modelo de detección binaria (XGBoost)
4. Aplicación de explicabilidad con SHAP
5. Evaluación funcional mediante escenarios TSTR
6. Análisis de resultados con enfoque forense

Consultar los scripts y los notebooks para la ejecución detallada.

---

## Metodología implementada

El sistema desarrollado incorpora:

* Generación sintética tabular (SDV)
* Clasificación binaria de tráfico de red
* Explicabilidad global y local con SHAP
* Evaluación estadística (KS) y funcional (TSTR)
* Separación entre evidencia original y derivados
* Diseño alineado con requisitos forenses

---

## Consideraciones forenses

El proyecto se ha diseñado teniendo en cuenta principios de análisis forense digital:

* Preservación de la evidencia original
* Separación de derivados de trabajo
* Reproducibilidad del pipeline
* Trazabilidad de transformaciones
* Interpretabilidad orientada a peritaje

---

## Licencia

Uso académico y de investigación.

---

## Contacto

Para cuestiones académicas relacionadas con el proyecto, consultar la memoria del PFM correspondiente.
