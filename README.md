# Enfermedades_del_corazon
# Análisis de Enfermedades del Corazón

Este proyecto realiza un análisis completo del dataset de enfermedades del corazón utilizando pandas, numpy, matplotlib y seaborn.

## Características del Análisis

### 1. Limpieza de Datos
- Eliminación de valores nulos y duplicados
- Corrección de valores atípicos e incorrectos
- Validación de rangos médicamente razonables

### 2. Filtración de Datos
- Subgrupos específicos (mayores de 50 años, mujeres con hipertensión, etc.)
- Análisis por características demográficas y clínicas

### 3. Funciones Agregadas
- Estadísticas descriptivas por grupos
- Operaciones en columnas (índice de riesgo cardiovascular)
- Clasificación de riesgo

### 4. Agrupaciones
- Por sexo y grupo de edad
- Por clasificación de riesgo
- Por presencia de diabetes

### 5. Consolidación de Datos
- Tabla consolidada con información clave
- Resúmenes estadísticos por categorías

### 6. Visualizaciones
- Distribución de edades
- Relación colesterol-enfermedad
- Comparación sexo-enfermedad
- Distribución de colesterol por edad
- Matriz de correlaciones
- Distribución de riesgo cardiovascular

### 7. Análisis y Conclusiones
- Interpretación de resultados
- Recomendaciones estratégicas
- Políticas de salud sugeridas

## Instalación

1. Instalar las dependencias:
```bash
pip install -r requirements.txt
```

2. Ejecutar el análisis:
```bash
python Enfermedades_del_corazon.py
```

## Estructura del Código

El código está organizado en 8 secciones principales:

1. **Carga y exploración inicial** - Descarga del dataset y exploración básica
2. **Limpieza de datos** - Eliminación de valores nulos, duplicados y atípicos
3. **Filtración de datos** - Creación de subgrupos específicos
4. **Funciones agregadas** - Estadísticas y operaciones en columnas
5. **Agrupaciones** - Agrupaciones por características relevantes
6. **Consolidación** - Tabla consolidada con información clave
7. **Visualización** - 6 gráficas diferentes para análisis visual
8. **Análisis y conclusiones** - Interpretación y recomendaciones

## Cumplimiento PEP8

El código sigue las reglas PEP8:
- Nombres de variables en snake_case
- Líneas de máximo 79 caracteres
- Espaciado consistente
- Comentarios descriptivos
- Docstrings para funciones principales

## Explicación del Código

Cada sección del código está explicada con comentarios detallados que describen:
- Qué hace cada operación
- Por qué se realizan las transformaciones
- Qué significan los resultados
- Cómo interpretar las visualizaciones

## Resultados

El análisis genera:
- Estadísticas descriptivas detalladas
- Visualizaciones informativas
- Conclusiones basadas en datos
- Recomendaciones estratégicas para políticas de salud
