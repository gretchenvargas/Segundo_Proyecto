# 📊 Análisis de Experimento A/B en Aplicación Móvil

Este proyecto analiza los resultados de un experimento A/B realizado en una aplicación móvil para evaluar el impacto de cambios en la interfaz sobre el comportamiento de los usuarios.

El estudio se basa en registros de eventos y busca determinar si las modificaciones implementadas generan mejoras significativas en la conversión.

---

## 📁 Contenido del Proyecto

- `Segundo_Proyecto.ipynb` → Análisis completo en Jupyter Notebook  
- `logs_exp_us.csv` → Dataset del experimento (no incluido)

---

## 🎯 Objetivo

El objetivo principal es:

- Analizar el comportamiento de los usuarios en un experimento A/B.
- Comparar grupos de control y grupo de prueba.
- Evaluar embudos de conversión.
- Validar estadísticamente los resultados.
- Determinar si los cambios implementados son efectivos.

---

## 🧹 Preparación de Datos

Durante el análisis se realizaron las siguientes tareas:

- Renombrado de columnas.
- Conversión de timestamps a formato de fecha.
- Creación de variables temporales.
- Verificación de valores nulos y duplicados.
- Limpieza y validación de registros.

---

## 📈 Análisis Realizado

El proyecto incluye:

- Exploración inicial de los datos.
- Análisis de volumen de eventos por grupo.
- Estudio del comportamiento de usuarios.
- Construcción del embudo de conversión.
- Comparación entre grupos.
- Visualizaciones con Matplotlib.

---

## 🧪 Pruebas de Hipótesis

Se aplicaron pruebas estadísticas para evaluar diferencias entre grupos:

- Comparación de tasas de conversión.
- Pruebas de significancia estadística.
- Análisis de proporciones.
- Validación de resultados con nivel de confianza.

Ejemplos de hipótesis evaluadas:

- No existen diferencias entre los grupos.
- El grupo experimental mejora la conversión.
- El cambio en la interfaz impacta el comportamiento.

---

## 🛠️ Tecnologías Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- SciPy  
- Jupyter Notebook  
