# Tipología y ciclo de vida de los datos
#### Práctica 2: Limpieza y análisis de datos

## El contexto
Esta práctica se ha realizado bajo el contexto de la asignatura Tipología y ciclo de vida de los datos, perteneciente al
Máster en Ciencia de Datos de la Universitat Oberta de Catalunya. En esta práctica se elabora un caso práctico orientado a aprender a identificar los datos
relevantes para un proyecto analítico y usar las herramientas de integración, limpieza, validación
y análisis de las mismas.

## Miembros del equipo
La actividad ha sido realizada conjuntamente por **Albert Casanova González** y **Xuan Zheng**.

## Objetivos del proyecto

#### 1. Descripción del dataset. ¿Por qué es importante y qué pregunta/problema pretende responder?

El dataset escogido es Titanic - Machine Learning from Disaster, facilitado como ejemplo en el enunciado de la asignatura, a través del siguiente enlace: https://www.kaggle.com/c/titanic

En este dataset encontramos información sobre los pasajeros que se encontraban a bordo en el último viaje del transatlántico RMS Titanic. Es un juego de datos “clásico” si hablamos de trabajar con algoritmos de clasificación, ya que contiene información sobre si los pasajeros sobrevivieron o no, haciéndolo interesante y siendo un buen punto de partida para practicar con este tipo de problemas.

El objetivo de trabajar con este conjunto de datos es el de comprender qué tipo de pasajeros era más probable que sobreviviera, analizando las variables de las que disponemos y tratando de dar respuesta a este problema.

#### 2. Integración y selección de los datos de interés a analizar. Puede ser el resultado de adicionar diferentes datasets o una subselección útil de los datos originales, en base al objetivo que se quiera conseguir.

Hemos decidido trabajar con el fichero train.csv, ya que es el que incorpora la variable “Survived”, a diferencia del fichero test.csv

Las variables que encontramos son:

-	PassengerId: ID que sirve para identificar a cada uno de los pasajeros
-	Survived: Indica si el pasajero sobrevivió o no. 0 = No, 1 = Yes
-	Pclass: Clase a la que pertenece el pasajero, según el ticket que compró. 1 = 1st, 2 = 2nd, 3 = 3rd
-	Name: Nombre del pasajero
-	Sex: Genero del pasajero
-	Age: Edad del pasajero
-	SipSp: Número de hermanos/as o marido/mujer a bordo del Titanic
-	Parch: Número de padres/madres o hijos/as a bordo del Titanic
-	Ticket: Número de ticket del pasajero
-	Fare: Coste del ticket
-	Cabin: Camarote del pasajero
-	Embarked: Puerto de embarque. C = Cherbourg, Q = Queenstown, S = Southampton

## Estructura del proyecto

* code/
  * code/prac2.Rmd
  * code/prac2.html
  * data/train.csv
  * data/train_clean.csv
* pdf/
  * pdf/titanic-analysis.pdf
* LICENSE
* README.md

1. La carpeta code/ contiene el fichero **prac2.Rmd** con el código en R utilizado, el fichero **prac2.html**. También los ficheros **train.csv** y **train_clean.csv**. Siendo train.csv el fichero inicial, y train_clean.csv el fichero final tras el análisis.
2. La carpeta pdf/ contiene el fichero **titanic-analysis.pdf** con las respuestas a las preguntas.
3. LICENSE contiene la licencia bajo la que se ha desarrollado el proyecto.
4. README.md es el archivo que estás leyendo, con la explicación del proyecto.


