# Diamond Price Prediction

![portada](https://github.com/Ironhack-Data-Madrid-Enero-2021/W7-Kaggle_competition/blob/main/images/PORTADA.jpg)

El objetivo de esta competición es la predicción del precio de los diamantes en función de sus características (peso, color, calidad de la talla, etc.), poniendo en práctica las mejores técnicas de machine learning.

Para ello se ha utilizado un dataset de kaggle  que podemos descargar [aquí](https://www.kaggle.com/competitions/diamonds-part-datamad0122/data). En este *dataset* nos podremos encontrar las siguientes variables:

- `id`: sólo para archivos de envío de pruebas y muestras, id para la identificación de muestras de predicción


- `price`: precio en USD


- `carat`: peso del diamante


- `cut`: calidad de la talla (aceptable, buena, muy buena, superior, ideal)


- `color`: color del diamante, de J (peor) a D (mejor)


- `clarity`: medida de la claridad del diamante (I1 (peor), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (mejor))


- `x`: longitud en mm


- `y`: anchura en mm


- `z`: profundidad en mm


- `depth`: porcentaje de profundidad total = z / media(x, y) = 2 * z / (x + y) (43--79)


- `table`: anchura de la parte superior del diamante en relación con el punto más ancho (43--95) 

[Caracteristicas_diamante](https://www.diamondstory.com.au/pub/media/wysiwyg/a.jpg)


# Librerías
- pandas
- numpy
- seaborn 
- matplotlib
- sidetable
- statsmodels 
- sklearn
- sys
- catboost
- pickle