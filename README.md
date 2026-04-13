📊 README – Análisis de Viviendas en Ames, Iowa
🧾 Descripción del Proyecto

Este proyecto tiene como objetivo el análisis exploratorio y visualización de datos del mercado inmobiliario en la ciudad de Ames, utilizando herramientas de Business Intelligence (Power BI).

El dataset contiene información detallada sobre propiedades residenciales, incluyendo características físicas, ubicación, condiciones estructurales, calidad de construcción y precios de venta.

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

Tabla principal: Información completa de las viviendas
Tabla de geolocalización: Latitud y longitud por Id
Relación:
Id (1:1 o 1:*) entre ambas tablas

Esto permite visualizaciones geográficas precisas en Power BI.
