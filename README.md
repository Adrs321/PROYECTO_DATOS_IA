# Predicción de Agotamiento de Stock en Retail

Este proyecto desarrolla una solución de Machine Learning para predecir el agotamiento de stock en productos de consumo masivo[cite: 3, 15]. [cite_start]El sistema permite anticipar quiebres de inventario en tiendas físicas y e-commerce, optimizando la reposición y mejorando la satisfacción del cliente[cite: 3, 8].

---

## Componentes del sistema

- **Módulos de Procesamiento**: Scripts para la ingesta de archivos CSV, limpieza de datos inconsistentes y transformación de variables[cite: 30, 67, 121].
- **Base de Datos PostgreSQL**: Almacenamiento estructurado del dataset analítico final[cite: 101, 109].
- **Motor de IA**: Modelo predictivo entrenado con Scikit-learn para estimar la probabilidad de agotamiento[cite: 102, 124].
- **Dashboard de Visualización**: Reporte interactivo para la interpretación de resultados y apoyo a la toma de decisiones[cite: 20, 103].
- **Documentación**: Planificación bajo estándares PMBOK y diseño técnico detallado[cite: 91, 118].

---

## Tecnologías utilizadas

- **Lenguaje**: Python 3 (Pandas, Scikit-learn)[cite: 71].
- **Base de Datos**: PostgreSQL[cite: 71, 123].
- **Versionamiento**: Git / GitHub[cite: 71, 87].
- **Metodología**: Gestión de proyectos basada en PMBOK[cite: 91, 142].

---

## Pipeline del Proyecto

| Etapa | Descripción |
| :--- | :--- |
| **1. Planificación** | [cite_start]Definición de alcance, WBS y cronograma de 5 semanas[cite: 93, 106, 112]. |
| **2. Diseño Técnico** | [cite_start]Arquitectura del sistema, componentes y modelo de datos[cite: 53, 60]. |
| **3. Ingesta y Limpieza** | [cite_start]Carga de ventas diarias y niveles de stock, con manejo de ruidos[cite: 22, 39, 108]. |
| **4. Carga en BD** | [cite_start]Persistencia de datos limpios en tablas relacionales[cite: 101, 133]. |
| **5. Modelado IA** | [cite_start]Entrenamiento de clasificación binaria para la variable `se_agotara`[cite: 41, 80, 109]. |
| **6. Visualización** | [cite_start]Implementación de indicadores clave y alertas de stock[cite: 33, 126]. |

---

## 📂 Estructura del repositorio

```text
prediccion-stock/
├── README.md               # Resumen del proyecto y guía de uso
├── docs/                   # Documentación técnica y de planificación
├── scripts/                # Código fuente modular
│   ├── ingesta.py          # Carga de datos inicial
│   ├── limpieza.py         # Preprocesamiento y validación
│   └── modelado.py         # Entrenamiento del modelo de IA
├── data/                   # Dataset histórico de ventas y stock
└── notebooks/              # Análisis exploratorio (EDA)
