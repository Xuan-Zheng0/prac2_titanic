# Tipología y ciclo de vida de los datos

#### 1. Descripción del dataset. ¿Por qué es importante y qué pregunta/problema pretende responder?

El dataset escogido es Titanic - Machine Learning from Disaster, facilitado como ejemplo en el enunciado de la asignatura, a través del siguiente enlace: https://www.kaggle.com/c/titanic

En este dataset encontramos información sobre los pasajeros que se encontraban a bordo en el último viaje del transatlántico RMS Titanic. Es un juego de datos “clásico” si hablamos de trabajar con algoritmos de clasificación, ya que contiene información sobre si los pasajeros sobrevivieron o no, haciéndolo interesante y siendo un buen punto de partida para practicar con este tipo de problemas.

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

