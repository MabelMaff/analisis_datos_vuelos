# ✈️ Análisis de Reservas de Vuelos por Nivel Educativo 🧑‍🏫

## 📋 Descripción

Este repositorio contiene la resolución del ejercicio final del Módulo 3, que tiene como objetivo evaluar las diferencias en las reservas de vuelos según el nivel educativo de los clientes. A continuación, encontrarás una descripción detallada de cada fase y los pasos realizados.

---

## 📂 Contenidos del Repositorio

1. **Exploración y Limpieza de Datos**
    - **Exploración Inicial:**
      - Realizar una exploración inicial de los datos para identificar posibles problemas, como valores nulos, atípicos o datos faltantes en las columnas relevantes.
      - Utilizar funciones de Pandas para obtener información sobre la estructura de los datos, la presencia de valores nulos y estadísticas básicas de las columnas involucradas.
      - Unir los dos conjuntos de datos de la forma más eficiente.
    - **Limpieza de Datos:**
      - Eliminar o tratar los valores nulos en las columnas clave para asegurar que los datos estén completos.
      - Verificar la consistencia y corrección de los datos.
      - Realizar ajustes o conversiones necesarias en las columnas (por ejemplo, cambiar tipos de datos) para garantizar la adecuación de los datos para el análisis estadístico.

2. **Visualización de Datos**
    - **Análisis Gráfico:**
      - ¿Cómo se distribuye la cantidad de vuelos reservados por mes durante el año?
      - ¿Existe una relación entre la distancia de los vuelos y los puntos acumulados por los clientes?
      - ¿Cuál es la distribución de los clientes por provincia o estado?
      - ¿Cómo se compara el salario promedio entre los diferentes niveles educativos de los clientes?
      - ¿Cuál es la proporción de clientes con diferentes tipos de tarjetas de fidelidad?
      - ¿Cómo se distribuyen los clientes según su estado civil y género?

3. **Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo**
    - **Preparación de Datos:**
      - Filtrar el conjunto de datos para incluir únicamente las columnas relevantes: 'Flights Booked' y 'Education'.
    - **Análisis Descriptivo:**
      - Agrupar los datos por nivel educativo y calcular estadísticas descriptivas básicas (como el promedio, la desviación estándar, los percentiles) del número de vuelos reservados para cada grupo.
    - **Prueba Estadística:**
      - Realizar una prueba de A/B testing para determinar si existe una diferencia significativa en el número de vuelos reservados entre los diferentes niveles educativos.

---

## 🗂️ Archivos del Repositorio

- **Notebooks:**
  - Evaluacion_Final_Modulo03.ipynb
 
- **PDFs**
  - Informe Análisis de Datos.pdf (Informe de cada una de als gráficas)
  - Informe Análisis de Datos 2.pdf (Informe resultante de evaluar las diferencias en las reservas de vuelos según el nivel educativo de los clientes)

- **Datasets:**
  - Customer Loyalty History.csv (original)
  - Customer Flight Activity.csv (original)
  - flight_activity_clean.csv (limpio)
  - loyalty_history_clean.csv (limpio)
  - Clean_data_flights_and_loyalty.csv (final)
---

## 🛠️ Tecnologías Utilizadas

- **Python**: Análisis y manipulación de datos.
- **Pandas**: Manipulación y análisis de datos.
- **Matplotlib/Seaborn**: Visualización de datos.
- **SciPy**: Pruebas estadísticas y análisis.

---

## 🧑‍🔬 Metodología

1. **Exploración y Limpieza de Datos**:
    - **Exploración Inicial**:
        - 🕵️‍♂️ Inspección de datos en busca de valores nulos y atípicos.
        - 📊 Uso de funciones de Pandas para obtener estadísticas básicas.
        - 🔗 Unificación eficiente de los conjuntos de datos.
    - **Limpieza de Datos**:
        - 🚫 Eliminación/tratamiento de valores nulos.
        - ✔️ Verificación de consistencia y corrección de datos.
        - 🔄 Ajustes y conversiones necesarias para un análisis adecuado.

2. **Visualización de Datos**:
    - 🌍 Distribución geográfica de los clientes.
    - 📅 Distribución mensual de vuelos reservados.
    - 📏 Relación entre la distancia de vuelos y puntos acumulados.
    - 💼 Comparación del salario promedio según nivel educativo.
    - 💳 Proporción de clientes con diferentes tarjetas de fidelidad.
    - 👥 Distribución de clientes por estado civil y género.

3. **Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo**:
    - **Preparación de Datos**:
        - 📑 Filtrado de columnas relevantes: 'Flights Booked' y 'Education'.
    - **Análisis Descriptivo**:
        - 📐 Cálculo de estadísticas descriptivas por nivel educativo.
    - **Prueba Estadística**:
        - 🧪 Realización de una prueba A/B testing (ANOVA) para evaluar diferencias significativas en las reservas de vuelos.

---

## 📈 Resultados

- **Análisis Descriptivo**:
  - Se presentan las estadísticas básicas para cada nivel educativo.
- **Prueba ANOVA**:
  - Resultados significativos que indican diferencias en las reservas de vuelos según el nivel educativo.

---

## 📊 Visualizaciones

- Incluyo gráficos que muestran las distribuciones y relaciones encontradas en los datos, proporcionando una visión clara y detallada del comportamiento de los clientes según su nivel educativo y otros factores demográficos.

---

## 🤝 Contribuciones

¡Todas las contribuciones son bienvenidas! Por favor, abre un 'issue' para discutir cualquier cambio importante antes de realizar un pull request.

---

## 📞 Contacto

Para cualquier consulta o sugerencia, puedes contactarme en:

- **LinkedIn**: [Tu Perfil de LinkedIn](www.linkedin.com/in/mabelmr)

---

¡Gracias por visitar este repositorio! Esperao que encuentres útil la información proporcionada. 🐱‍🚀

