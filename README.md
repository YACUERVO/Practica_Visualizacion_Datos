📊 Análisis de Viviendas en Ames, Iowa — Power BI
🧾 Descripción del Proyecto

Práctica de análisis exploratorio del mercado inmobiliario de Ames usando Power BI. El dataset tiene información de propiedades residenciales: características físicas, ubicación, calidad de construcción y precios de venta. La idea es entender qué variables mueven el precio.

El propósito principal es identificar patrones, tendencias y variables clave que influyen en el precio de las viviendas.

🎯 Objetivos
Analizar los factores que afectan el precio de venta (SalePrice).
Evaluar la influencia de variables como:
Ubicación (Neighborhood)
Calidad general (OverallQual)
Área habitable (GrLivArea)
Visualizar la distribución geográfica de las propiedades mediante coordenadas (latitud y longitud).
Generar insights útiles para toma de decisiones inmobiliarias.

🗂️ Estructura de los Datos

El dataset incluye más de 80 variables, clasificadas en:

🏠 Características de la propiedad
MSSubClass: Tipo de vivienda
HouseStyle: Estilo de la casa
BldgType: Tipo de construcción
YearBuilt: Año de construcción
📍 Ubicación
Neighborhood: Barrio dentro de Ames
LotArea: Tamaño del lote
LotFrontage: Frente del lote
🏗️ Calidad y condición
OverallQual: Calidad general
OverallCond: Condición general
ExterQual: Calidad exterior
🏡 Espacios y dimensiones
GrLivArea: Área habitable
TotalBsmtSF: Área del sótano
GarageArea: Área del garaje
💰 Información de venta
SalePrice: Precio de venta
SaleCondition: Condición de venta
YrSold: Año de venta

🔗 Modelo de Datos

El modelo está compuesto por:

Dos tablas conectadas por Id:
  -Tabla principal con los datos de cada vivienda
  -Tabla de geolocalización con latitud y longitud
Relación:
Id (1:1 o 1:*) entre ambas tablas


📊 Análisis de Indicadores (KPIs)
💰 1. Objetivo de facturación anual

Valor actual: 31,04 mil
Objetivo: 60 mil
Cumplimiento: -48,26 %

KPIs analizados

Facturación anual: 31,04 mil vs objetivo de 60 mil → cumplimiento del 52%. Hay una brecha importante que sugiere revisar el volumen de ventas o los objetivos.

📌 Insight:
Existe una brecha considerable frente al objetivo.
Indica bajo rendimiento en ventas acumuladas.
Se requiere ajustar estrategias comerciales o revisar metas.

📅 2. Objetivo de facturación mensual

Facturación mensual: 0,73 mil vs objetivo de 5 mil → solo el 14,6% del objetivo. El bajo desempeño no es solo histórico: está pasando ahora.

Valor actual: 0,73 mil
Objetivo: 5 mil
Cumplimiento: -85,39 %

🧠 Interpretación:

El rendimiento mensual es crítico, con un cumplimiento muy bajo frente al objetivo, lo que indica una desaceleración importante en las ventas recientes.

🎯 3. Promedio de venta vs objetivo

Valor actual: 180,92 mil

🧠 Interpretación:

Precio promedio: 180,92 mil. Este número se mantiene estable, lo que indica que el problema no está en los precios sino en cuántas propiedades se venden.

Aunque el precio promedio de las propiedades es adecuado (180,92 mil), los indicadores muestran un bajo cumplimiento tanto mensual como anual, lo que sugiere que el problema principal radica en el volumen de ventas y no en el valor de los inmuebles.

📊 Análisis de Visualizaciones
🏘️ Promedio de ventas por barrio
🧠 Interpretación:

Se observan diferencias significativas en el precio promedio de las viviendas según el barrio.

📌 Insights:
Barrios como NridgHt (Northridge Heights) y StoneBr (Stone Brook) presentan los precios más altos.
Barrios como IDOTRR y MeadowV tienen los precios más bajos.
Existe una clara segmentación del mercado por ubicación.
🔥 Conclusión:

La ubicación es uno de los factores más determinantes en el valor de las propiedades.

📈 Promedio de ventas y área por mes
🧠 Interpretación:

Se observa una relación entre el precio promedio y el área habitable a lo largo del tiempo.

📌 Insights:
Meses como septiembre y noviembre presentan picos en precios.
Existe una correlación positiva:
A mayor área (GrLivArea), mayor precio.
Se evidencian fluctuaciones mensuales (posible estacionalidad).
🔥 Conclusión:

El comportamiento del mercado varía por mes, pero mantiene una relación directa entre tamaño de la vivienda y precio.

📊 Embudo (Suma de cantidad por etapa)
🧠 Interpretación:

Representa la reducción progresiva de registros desde el total de viviendas hasta las variables más específicas.

📌 Insights:
Total de viviendas: 1460
Reducción significativa al analizar:
Calidad
Área habitable
Precio
Solo una pequeña proporción cumple todas las condiciones analizadas.
🔥 Conclusión:

A medida que se aplican criterios más específicos, el volumen de datos disminuye, lo que permite enfocar el análisis en propiedades más relevantes.

🗺️ Mapa – Promedio del área por vivienda
🧠 Interpretación:

Muestra la distribución geográfica de las viviendas y su concentración en la ciudad.

📌 Insights:
Alta concentración de propiedades en zonas urbanas.
Se identifican clusters de viviendas.
Promedio de área: 1515,46 pies²
Total de viviendas: 1460
🔥 Conclusión:

La distribución geográfica permite identificar zonas con mayor densidad de viviendas y potenciales áreas de análisis del mercado.

📉 Indicadores adicionales
Precio mínimo: 34,900
Precio máximo: 755,000
📌 Insight:

Existe una alta variabilidad en los precios, lo que confirma la diversidad del mercado inmobiliario.

🧠 Conclusión General del Dashboard

El análisis evidencia que el mercado inmobiliario en Ames está altamente influenciado por la ubicación, el tamaño de la vivienda y la calidad de construcción. Además, se identifican variaciones temporales en los precios, así como una clara segmentación geográfica del mercado.

El mercado en Ames está influenciado principalmente por ubicación, tamaño y calidad de construcción. Los indicadores de cumplimiento muestran un problema de volumen de ventas, no de precios. Las variaciones mensuales sugieren cierta estacionalidad que vale la pena explorar más.
