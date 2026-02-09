# eph-nea-laboral
Observatorio laboral del NEA basado en EPH
# Análisis del Mercado Laboral - Región NEA (EPH-INDEC)

Este proyecto realiza un análisis estadístico y descriptivo de la situación laboral en el **Nordeste Argentino (NEA)**, abarcando los aglomerados de Corrientes, Gran Resistencia, Formosa y Posadas. Se utilizan los microdatos oficiales de la **Encuesta Permanente de Hogares (EPH)** provistos por el **INDEC**.

## 🎯 Objetivos del Análisis
* Calcular las tasas principales (Actividad, Empleo y Desocupación) para la región.
* Analizar la **brecha de género** en el acceso al mercado de trabajo.
* Identificar niveles de **informalidad laboral** y precariedad según el nivel educativo.
* Comparar el desempeño socioeconómico entre los distintos aglomerados del NEA.

## 🛠️ Herramientas y Metodología
* **Python / Pandas:** Limpieza de datos y unión de bases trimestrales.
* **Estadística:** Aplicación de factores de expansión (`PONDERA`) para la representatividad poblacional.
* **Visualización:** Seaborn y Matplotlib para la creación de reportes gráficos.
* **Dominio del Tema:** Conocimiento de la metodología INDEC para el tratamiento de variables como `ESTADO`, `CAT_OCUP` y `P21`.

## 📈 Hallazgos Principales (Insights)
* **Tasa de Desocupación:** Se identificó que en el aglomerado de [Nombre del aglomerado] la desocupación alcanzó un [X]%.
* **Brecha de Género:** Las mujeres en la región NEA perciben en promedio un [X]% menos de ingresos por ocupación principal que los varones.
* **Educación vs. Empleo:** El [X]% de los trabajadores con estudios superiores completos se encuentran en el sector formal, frente a un [X]% en el sector informal.

## 📂 Estructura del Repositorio
* `/data`: Instrucciones para descargar los microdatos del INDEC (no se suben archivos pesados por .gitignore).
* `/notebooks`: Jupyter Notebooks detallados con el paso a paso del análisis.
* `/outputs`: Gráficos y tablas resumen generadas.

## 🚀 Cómo Reproducir el Análisis
1. Clonar el repositorio: `git clone https://github.com/maidanaignacio/eph-nea-laboral.git`
2. Instalar dependencias: `pip install -r requirements.txt`
3. Ejecutar el notebook principal para generar los indicadores actualizados.

---
**Contacto:** [Tu Nombre] - [Tu LinkedIn o Email]
