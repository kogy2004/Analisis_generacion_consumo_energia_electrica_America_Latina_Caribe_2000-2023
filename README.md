# Análisis de Generación y Consumo de Energía Eléctrica en América Latina y el Caribe (2000–2023)

Este proyecto realiza un análisis comparativo sobre la generación y consumo de electricidad en América Latina y el Caribe entre los años 2000 y 2023. Utilizando datos oficiales del Hub de Energía del BID y OLADE, se identifican patrones históricos, tendencias por sectores y evolución de las fuentes energéticas, destacando el papel de las energías renovables.

## 📊 Objetivo General

Analizar la evolución y distribución de la generación eléctrica y consumo por sectores (hidroeléctrica, térmica, solar, eólica, entre otras) en América Latina y el Caribe entre 2000 y 2023.

## 🎯 Objetivos Específicos

- Identificar la evolución de la generación por fuente.
- Examinar el consumo eléctrico por sector económico.
- Evaluar la penetración de energías renovables en la región.

## 🗃️ Fuente de Datos

Los datos fueron extraídos del Hub de Energía para América Latina y el Caribe respaldado por:
- [Banco Interamericano de Desarrollo (BID)](https://hubenergia.org/)
- [Organización Latinoamericana de Energía (OLADE)](https://www.olade.org/)

## 🧹 Procesamiento de Datos

- **Limpieza**: corrección de errores tipográficos, ajuste de tipos de datos y tratamiento de valores nulos.
- **Transformación**: segmentación de países/regiones, filtrado temporal (2000–2023), tratamiento de ceros y valores atípicos.
- **Visualización**: gráficos de tendencias, mapas de calor, matrices de correlación y participación por fuente.

## 📈 Análisis Incluido

- Tendencias de generación eléctrica por fuente y región.
- Distribución del consumo eléctrico por sector (industrial, residencial, comercial, etc.).
- Comparación regional del crecimiento del consumo.
- Evaluación de participación de fuentes renovables vs. no renovables.
- Prueba estadística T-Student entre periodos (2000–2011 vs. 2012–2023).
- Correlaciones entre sectores de consumo y entre fuentes de generación.

## 🗺️ Resultados Clave

- Alta dependencia de la hidroelectricidad como fuente renovable.
- Crecimiento significativo en el consumo residencial e industrial.
- Chile y Brasil muestran avances en diversificación energética con solar y eólica.
- Riesgos asociados a fenómenos climáticos que afectan la matriz hidroeléctrica dominante.
- Oportunidades de mejora en el sector transporte y en diversificación renovable.

## 🛠️ Tecnologías Utilizadas

- Python + Google Colab
- Pandas, NumPy, Matplotlib, Seaborn
- Estadística descriptiva e inferencial (prueba T)
- Visualización avanzada

## 👨‍💻 Equipo de Trabajo

- Alejandro Soto Prado  
- Juan Esteban Giraldo Doria  
- Kogy Isaza Jaramillo  
- Leslin Jhoana Puerta García  

Bootcamp de Análisis de Datos – TalentoTech  
Institución Universitaria de Envigado – 2025  

## 📚 Referencias

- https://hubenergia.org/
- https://sielac.olade.org/
- https://www.olade.org/publicaciones/manual-estadistica-energetica-2017/
- https://hubenergia.org/sites/default/files/2024-03/Metadatos_generacion_capacidad_consumo_energia.pdf


## 📌 Recomendaciones

Este proyecto puede servir como base para análisis energéticos futuros, diseño de políticas públicas o inversiones en infraestructura sostenible. Se recomienda actualizar los datos anualmente y profundizar en análisis por país o subregión.
