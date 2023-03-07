# Competencia_Salarios
![Distribucion de Titulos de Data](https://github.com/lohe040789/Competencia_Salarios/blob/main/Imagenes/Imagen1.png)

## Predicción de sueldo

Vamos a ver cómo crear un modelo de machine learning que pueda determinar el sueldo de una persona en el mundo de Data Science  según información de ubicacion y titulos de la persona como caracteristicas de la misma empresa.

## Transformacion de los datos

Nos enfocaremos en cambiar los datos categoricos a cuantitativo tratando de mantener una relacion coherente con los datos. Aplicando metodos como :

`Encoded`: codifica etiquetas de una característica categórica en valores numéricos entre 0 y el número de clases.

`One Hot Encoding`: crear una columna para cada valor distinto que exista en la característica que estamos codificando y, para cada registro, marcar con un 1 la columna a la que pertenezca dicho registro y dejar las demás con 0.

Como parte del testeo cambiamos los valores de paises por el PIB (producto interior bruto) de cada uno de ellos, tratando de hacer una relacion entre los datos y la ubicacion tanto de la empresa como la persona.

![Paises que ofrecen mas puestos de data](https://github.com/lohe040789/Competencia_Salarios/blob/main/Imagenes/Imagen2.png)


## Modelo

Para tener una referencia utilizamos H20 (una plataforma Machine Learning open-source) y nos da el mejor modelo de acuerdo con nuestra tranformacion de los datos para predecir los salarios con la Transformacion que hemos hecho a los datos.

Como Resultado obtuvimos un RMSE: 41571.59477