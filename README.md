```markdown
# 📱 Análisis de Comportamiento de Usuarios - ConnectaTel

🎯 Objetivo del Proyecto
Este proyecto analiza el comportamiento de uso de servicios móviles (llamadas y mensajes) de ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia.

### Objetivos específicos:
- Identificar patrones de uso de llamadas y mensajes por segmentos de clientes
- Detectar comportamientos atípicos que puedan indicar fraude o errores de registro
- Analizar cómo varía el uso según edad y tipo de plan contratado
- Generar insights comerciales para optimizar la oferta y mejorar la experiencia del usuario

📊 Datasets Utilizados
El análisis se basa en tres fuentes principales de datos:

Dataset	Descripción	Contenido Principal
plans.csv	Catálogo de planes	Precios, minutos incluidos, GB, costos extra
users_latam.csv	Información de clientes	Edad, ciudad, fecha registro, plan contratado
usage.csv	Detalle de uso real	Llamadas (duración), mensajes (longitud)

🔍 Etapas del Análisis
### 1. Exploración y Limpieza de Datos
- Carga y exploración inicial de los tres datasets
- Identificación de valores faltantes y duplicados
- Estandarización de tipos de datos
- Validación de consistencia entre tablas

### 2. Integración de Datos
- Merge de las tres fuentes de información
- Creación de métricas agregadas por usuario
- Manejo de usuarios sin registros de actividad

### 3. Análisis Estadístico Descriptivo
- Perfiles estadísticos de uso por cliente
- Análisis de distribuciones de llamadas y mensajes
- Segmentación por edad, país y plan

### 4. Detección de Outliers
- Aplicación del método IQR (Rango Intercuartílico)
- Identificación de comportamientos atípicos
- Análisis de posibles causas de valores extremos

### 5. Segmentación de Clientes
- Creación de grupos de uso (alto, moderado, bajo)
- Análisis comparativo entre segmentos
- Identificación de patrones por demografía

### 6. Visualización y Insights
- Gráficos de distribuciones y comparaciones
- Visualización de outliers y patrones
- Extracción de insights comerciales
