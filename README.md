# Explorando el Éxito Académico

Este proyecto tiene como objetivo desarrollar un modelo predictivo de aprendizaje automático para identificar estudiantes en riesgo de bajo rendimiento académico. Mediante el análisis de datos históricos, como calificaciones, características demográficas y datos escolares, buscamos proponer estrategias para mejorar el rendimiento estudiantil.

---

## Descripción del Proyecto

### Objetivo
Crear un modelo de machine learning que permita identificar proactivamente a los estudiantes con bajo rendimiento académico. Esto ayudará a los departamentos académicos a implementar estrategias específicas para apoyar a estos estudiantes.

### Interesados Clave
- **Subdirección Académica**
  - **Departamento de Desarrollo Académico**
    - **Orientación Educativa**: Ofrece apoyo académico personalizado.
    - **Coordinación de Carrera**: Diseña estrategias específicas por área académica.

---

## Datos Utilizados

El modelo utiliza cuatro fuentes principales de datos:

1. **Calificaciones**:
   - Período, clave del alumno, clave de materia, calificación, tipo de calificación.

2. **Carrera**:
   - Clave de carrera, nombre, nombre corto.

3. **Escuelas**:
   - Clave, nombre de la escuela.

4. **Estudiantes**:
   - Clave del alumno, clave de carrera, sexo, preparatoria de origen, ubicación residencial, entre otros.

### Limpieza y Preparación
- Se identificaron y corrigieron inconsistencias en los datos (valores nulos, formatos incorrectos, claves inválidas).
- Herramientas utilizadas: 
  - **Python**: Librerías como `Pandas` y `Scikit-learn`.
  - **Excel**: Para visualización y verificación de datos.

---

## Modelado Predictivo

### Algoritmo
Se implementaron y compararon dos modelos de machine learning:
- **Random Forest Regressor** (modelo seleccionado)
- **XGB Regressor**

### Métricas de Evaluación
- **MAE (Mean Absolute Error)**: Utilizado para medir la precisión del modelo.

### Resultados
- El modelo Random Forest Regressor mostró un MAE de 10.33%, reflejando un buen desempeño.
- Predicciones cercanas a valores reales y consistencia en los pliegues del dataset evaluados.

---

## Análisis de Resultados

### Principales Hallazgos
- El 18.8% de los estudiantes está en riesgo de bajo rendimiento.
- El riesgo varía según:
  - **Sexo**: Mayor riesgo en hombres (21.08%) que en mujeres (10.9%).
  - **Preparatoria de origen**: Mayor incidencia de riesgo en C.B.T.I.S 244.
  - **Carreras académicas**: Sistemas tiene un 29% de estudiantes en riesgo.

---

## Acciones Propuestas

1. **Programas de Tutorías y Asesorías Personalizadas**:
   - Dirigidas a estudiantes en riesgo, enfocadas en las áreas críticas.
   
2. **Capacitación a Docentes**:
   - Herramientas pedagógicas específicas para apoyar a estudiantes identificados.

3. **Ampliación de Variables**:
   - Incorporar datos adicionales (asistencia, actividades extracurriculares, evaluaciones cualitativas) para mejorar la precisión del modelo.

4. **Monitoreo Continuo**:
   - Actualización periódica del modelo con nuevos datos para mantener su efectividad.

---

## Herramientas Utilizadas

- **Lenguaje**: Python
- **Librerías**: Pandas, Scikit-learn, Random Forest Regressor, XGB Regressor.
- **Visualización y Soporte**: Excel.

---

## Contribuciones

Desarrollado por el equipo:
- **Jacquelin Robles Ríos**
- **Miguel Ángel Peña López**

Docente: Pedro Villa Casas

