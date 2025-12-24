# Analisis-del-mercado-de-Steam
Usando el dataset de Kaggle llamado "Steam Games Dataset 2021-2025 (65k+)" se hizo un análisis básico de distintos factores.

## Descripción del Proyecto
Este proyecto analiza el dataset extraido de Kaggle, "Steam Games Dataset 2021-2025 (65k+)" para identificar tendencias en los géneros más populares post pandemia y determinar si existe una relación entre el precio de venta y el éxito del juego (medido en recomendaciones).

# Herramientas Utilizadas
**Python:** Lenguaje principal.

**Pandas:** Limpieza y transformación de datos (uso de .explode() para manejo de géneros).

**Seaborn & Matplotlib:** Visualización de datos y análisis estadístico.

# Hallazgos Principales

## **1. Dominio de Géneros**
En este periodo post-pandemia, el género Indie no solo es una categoría, es el motor de Steam. La democratización de herramientas como Unity y Unreal Engine permitió que, entre 2021 y 2025, el volumen de lanzamientos independientes superara récords históricos, saturando la plataforma pero también diversificando la oferta más que nunca.
<img width="911" height="548" alt="image" src="https://github.com/user-attachments/assets/2e44a400-e2f6-46ab-b6b9-5216a8f76f9f" />

## **2. Análisis de precios** 
Mientras que los juegos Indie mantienen precios bajos para competir en un mercado saturado (muchas veces por debajo de los 10 USD), géneros como de 'Deportes o 'RPG' han logrado mantener —e incluso subir— sus precios. Esto ocurre porque estos géneros suelen atraer a un público muy fiel, dispuesto a pagar un precio elevado independiente.
<img width="1298" height="548" alt="image" src="https://github.com/user-attachments/assets/0e217e66-10c7-41b1-a23d-7b3c070ca685" />

## **¿El precio garantiza el éxito?** 
¿El precio garantiza el éxito?
Tras analizar la correlación entre el precio y las recomendaciones, se obtuvo un coeficiente de 0.06.

## Conclusión: 
La relación entre precio y calidad es practicamente nula, esto es visto en mayor medida en este periodo, ya que entre 2021 y 2025, hemos visto el auge de los "hits virales" (muchas veces gratuitos o muy baratos) que, gracias a redes sociales y streamers, logran millones de recomendaciones, superando en visibilidad a grandes producciones de 70 USD que no logran conectar con la comunidad.
<img width="1017" height="1011" alt="image" src="https://github.com/user-attachments/assets/97cfe43d-2bd8-4802-84d7-9ee3f1c5a974" />

## Cómo ejecutar el notebook?
Clona el repositorio.

Asegúrate de tener instalado pandas, seaborn y matplotlib.

Ejecuta el archivo analisis_steam.ipynb.

