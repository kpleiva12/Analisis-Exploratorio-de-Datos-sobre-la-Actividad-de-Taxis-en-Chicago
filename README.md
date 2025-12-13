# Análisis-Exploratorio-de-Datos-sobre-la-Actividad-de-Taxis-en-Chicago
Proyecto que analiza patrones de viajes en taxi mediante Python y SQL, incluyendo distribución de trayectos, desempeño por compañías y relación entre clima y duración de viajes. Incluye limpieza de datos, visualizaciones e hipótesis estadísticas.

Se presenta en este repositorio un documento con el registro de las salidas obtenidas mediante SQL y un jupyter notebook con el código realizado con lenguaje python 

Objetivo
Identificar patrones de demanda, principales zonas de destino y evaluar impacto del clima en la duración de los viajes.

Tecnologías usadas
Python, pandas, NumPy, matplotlib, scipy.

Resultado/Insight clave
Top 10 neighborhoods identificados.
Variación en volumen de viajes por compañía.
Visualizaciones claras de tendencias.
Prueba estadística confirmando o refutando la hipótesis sobre clima vs duración.

Competencias clave aplicadas:

1. Modelado de datos y comprensión de esquemas relacionales
    Identificación de claves (primary y foreign keys).
    Comprensión de relaciones entre entidades (Zuber: cabs, trips, weather_records, neighborhoods).
   
2. Consultas SQL intermedias y avanzadas
  JOINs basados en timestamps (no en llaves primarias).
  Filtros condicionales.
  Group By, Order By, agregaciones.
  Subconsultas y Common Table Expressions (CTEs).
  Análisis temporal (por hora, día, sábado, clima).

3. Análisis exploratorio (EDA)
  Análisis de distribución de viajes.
  Identificación de patrones por hora, día de semana, barrios, distancia y duración.
  Comparación por empresa de taxi.

4. Integración de datos externos (weather_records)
  Enlace de datasets heterogéneos por variable temporal.
  Limpieza de datos de clima.
  Unión de fuentes para encontrar correlaciones.

5. Prueba de hipótesis con datos reales
  Duración de viajes Loop → O'Hare.
  Comparación de viajes en condiciones normales vs sábados con lluvia.
  Uso de estadística descriptiva e inferencial.
  Validación o rechazo de hipótesis con SQL + análisis posterior.
