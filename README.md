# Resumen Ejecutivo: Predicción de Elección de Carrera en "Eddis" 🎓

### 📌 Descripción General
Este proyecto consiste en el desarrollo de un modelo de **Machine Learning** diseñado para la empresa educativa **"Eddis"**. El objetivo principal es analizar el perfil de los interesados en las sedes de **Ezeiza, Cañuelas y Monte Grande** para predecir qué tipo de formación elegirán.

A través de la visualización de datos y el modelado predictivo, el trabajo busca responder a la pregunta central:
> *¿En qué medida los factores demográficos, laborales y temporales definen la categoría de estudio que un aspirante seleccionará?*

---

### 🎯 Objetivo del Proyecto
Desarrollar un modelo de clasificación capaz de **determinar la Categoría del Plan de Estudio** (Salud, Técnica, Estética, etc.) basándose en variables personales y del entorno, permitiendo a la empresa optimizar sus estrategias de venta y oferta académica.

### 📂 Dataset
* **Fuente:** Datos internos de inscripciones (Sedes: Ezeiza, Cañuelas, Monte Grande).
* **Registros:** 3,833 registros procesados.
* **Variable Objetivo:** Categoria (Plan de Estudio).

### ❓ Hipótesis de Trabajo (Validadas)
* **Edad:** Es un predictor clave; las categorías tecnológicas atraen perfiles más jóvenes.
* **Género:** Existe una marcada segmentación en rubros como Estética y Salud.
* **Socio-Laboral:** El estatus de empleo y nivel educativo influye en la búsqueda de capacitación rápida.
* **Estacionalidad:** La demanda de categorías varía significativamente según el mes del año.

---

### 🤖 Modelado y Evaluación
Se implementó un modelo de **Random Forest Classifier**, seleccionado por su robustez para manejar variables categóricas.

* **Precisión (Accuracy):** Se alcanzó un nivel cercano al **35%**, superando la probabilidad del azar (~12%).
* **Herramienta de Diagnóstico:** Se utilizó una **Matriz de Confusión** que reveló una alta eficacia prediciendo áreas como **Salud** y **Estética**, identificando a su vez solapamientos en perfiles de **Negocios** y **Oficios**.

### 🧾 Conclusiones Finales
Los resultados confirman que la elección de carrera en Eddis sigue patrones demográficos claros. La implementación de este modelo permite a la empresa anticipar la demanda y personalizar la atención. Para futuras iteraciones, se recomienda capturar datos sobre **intereses vocacionales** y **nivel de ingresos** para romper el techo actual de precisión.

---
**Autor:** [Tu Nombre]  
*Proyecto Final - Curso Data Science I*
