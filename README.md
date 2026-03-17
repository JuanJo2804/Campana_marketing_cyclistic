# Caso de Estudio: Análisis de Movilidad en Cyclistic (Chicago)
### *De Ciclistas Ocasionales a Miembros Anuales*

## 1. Descripción del Proyecto
Este proyecto se desarrolla en el rol de un **Analista de Datos Junior** para **Cyclistic**, una empresa de bicicletas compartidas en Chicago. El objetivo central es maximizar la rentabilidad de la compañía mediante la **conversión de ciclistas ocasionales en miembros anuales**, ya que este último segmento representa la base financiera más estable y rentable para el negocio. 

A través del análisis de **423,120 registros** históricos de viajes (Q1-2020), busqué responder una pregunta clave: **¿Cómo usan las bicicletas de Cyclistic los miembros anuales y los ciclistas ocasionales de manera diferente?**.

## 2. Metodología y Proceso (Las 6 Fases de Análisis)

Para garantizar la integridad de los resultados, seguí el proceso de análisis de datos de Google:

*   **Preguntar:** Definí la tarea de negocio centrada en identificar patrones de uso diferenciados para diseñar una estrategia de marketing digital basada en datos.
*   **Preparar:** Utilicé datos públicos de **Motivate International Inc.** (Divvy Trips) bajo estándares **ROCCC**. Aseguré la privacidad de los datos (PII) mediante la anonimización de la información personal de los usuarios.
*   **Procesar:** Utilicé **Microsoft Excel** para la limpieza de datos. Los pasos críticos incluyeron:
    *   **Normalización de coordenadas:** Corregí formatos alterados mediante lógica condicional para asegurar la precisión geográfica en Chicago (~41.xx, ~-87.xx).
    *   **Depuración de "ruido":** Eliminé 3,765 registros de mantenimiento (estación "HQ QR") que inflaban artificialmente los datos.
    *   **Creación de métricas:** Calculé la duración del viaje (`ride_length`) y segmenté por día de la semana (`day_of_week`).
*   **Analizar:** Realicé un análisis descriptivo que reveló una "brecha de tiempo" de **8 a 1**: mientras los miembros usan el sistema por 12 minutos en promedio, los ocasionales lo usan por **1 hora y 43 minutos**.
*   **Compartir:** Diseñé un **Dashboard interactivo** con mapas de calor y gráficos de barras que visualizan la "Doble Identidad" de Cyclistic: transporte laboral de lunes a viernes y plataforma de ocio los fines de semana.
*   **Actuar:** Elaboré recomendaciones estratégicas basadas en la ubicación geográfica (puntos recreativos) y el comportamiento temporal de los usuarios.

## 3. Descubrimientos Clave
*   **Patrón Laboral vs. Recreativo:** Los miembros anuales dominan los **martes** con viajes cortos y funcionales. Los ciclistas ocasionales triplican su actividad los **domingos**, realizando viajes exploratorios de larga duración.
*   **Ubicación Estratégica:** Los miembros se concentran en estaciones de transporte y oficinas (ej. Canal St & Adams St), mientras que los ocasionales inician sus viajes masivamente cerca de **parques y la costa del lago**.

## 4. Recomendaciones Principales
Basándome en el análisis, las tres acciones sugeridas son:

1.  **Campaña de "Beneficio de Lealtad":** Lanzar promociones digitales personalizadas para usuarios ocasionales frecuentes, demostrando el ahorro económico de la membresía anual frente al uso prolongado de pases diarios.
2.  **Promoción de Inclusividad:** Resaltar en redes sociales la disponibilidad de **bicicletas asistidas** para atraer a usuarios interesados en viajes recreativos de larga distancia con menor esfuerzo físico.
3.  **Enfoque en Conveniencia Funcional:** Posicionar la membresía como un **"Pase de Acceso Recreativo Ilimitado"**, enfocando el marketing digital en las estaciones costeras durante los fines de semana.

---

**Herramientas utilizadas:** Microsoft Excel (Tablas dinámicas, Fórmulas lógicas, Haversine para distancia esférica).
