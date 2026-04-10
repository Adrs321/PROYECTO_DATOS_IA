# Predicción de Agotamiento de Stock en Retail

Este proyecto tiene como objetivo desarrollar una solución técnica basada en Machine Learning que permita predecir con anticipación cuándo un producto se quedará sin stock. El sistema analiza patrones de demanda influenciados por la estacionalidad, promociones y tiempos de reposición para optimizar la toma de decisiones logísticas y reducir pérdidas económicas.

---

## Componentes del sistema

- **Scripts de procesamiento**: módulos dedicados a la ingesta, limpieza y transformación de datos históricos.
- **Base de datos PostgreSQL**: repositorio central para el almacenamiento del dataset analítico validado.
- **Modelo de IA (scikit-learn)**: motor de clasificación binaria para estimar la probabilidad de quiebre de stock.
- **Dashboard de visualización**: interfaz gráfica para la interpretación de resultados y métricas del modelo.
- **Documentación**: incluye la planificación estratégica basada en PMBOK y el diseño técnico detallado.

---

## Tecnologías utilizadas

- **Lenguaje**: Python 3 (Pandas, Scikit-learn)
- **Base de Datos**: PostgreSQL
- **Control de Versiones**: Git / GitHub
- **Metodología**: Enfoque de gestión de proyectos PMBOK

---

## Pipeline implementado

| Etapa | Descripción |
| :--- | :--- |
| **1. Planificación** | Definición de alcance, cronograma y hitos técnicos. |
| **2. Diseño Técnico** | Estructuración de componentes y modelo de datos. |
| **3. Ingesta y Limpieza** | Procesamiento de datos de ventas y manejo de inconsistencias. |
| **4. Carga en BD** | Migración del dataset limpio a tablas estructuradas en PostgreSQL. |
| **5. Modelado IA** | Entrenamiento y evaluación del modelo predictivo. |
| **6. Visualización** | Implementación del dashboard de resultados e insights. |

---

## 📂 Estructura del repositorio

```text
agotamiento-stock/
├── README.md               # Resumen del proyecto y guía de uso
├── docs/                   # Documento de planificación y diseño técnico
├── scripts/                # Código fuente modular
│   ├── ingesta.py          # Script de carga de datos inicial
│   ├── limpieza.py         # Tratamiento de nulos y duplicados
│   └── entrenamiento.py    # Generación del modelo predictivo
├── data/                   # Dataset histórico (CSV)
└── notebooks/              # Análisis exploratorio de datos (EDA)
