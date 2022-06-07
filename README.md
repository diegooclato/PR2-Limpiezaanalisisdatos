# PR2-Limpieza y Analisis de Datos

# Práctica 2: Limpieza y Analisis de Datos

## Titanic - Machine Learning from Disaster

### Equipo

Author: Diego Octavio Labastida Tolalpa

Esta práctica es realizada de manera individual.

### Fichero: Limpieza y anlaisis de datos/gender_submission.csv
### Fichero: Limpieza y anlaisis de datos/test.csv
### Fichero: Limpieza y anlaisis de datos/train.csv

3 ficheros correspondientes a la siguiente información dividido en ficheros de train, test, gender_submission. 

891 Registros y 12 variables correspondiente a la información del archivo train con información de pasajeros en el Titanic.
Los archivos test y gender_submission se complementan y deben unirse posteriortente para obetener 418 Registros con 12 variables.

Finalmente se obtendra un dataset de 1309 Registros y 12 variables.

- **PassengerId: (integer)**
    Id unico para cada pasajero del Titanic
    
- **Survived: (integer)**
    Indica si el pasajero sobrevivio o no (1=sobrevivio, 0=No sobrevivio)
    
- **Pclass: (integer)**
    Clase del ticket de los pasajeros 1er, 2da y 3ra clase.

- **Name: (character)**
    Nombre del Pasajero

- **Sex: (character)**
    Genero del pasajero (Male / Female) Hombre o Mujer

- **Age: (numeric)**
    Edad del pasajero
    
- **SibSp: (integer)**
    Numero de hermanos a bordo del Titanic

- **Parch: (integer)**
    Numero de padres abordo del Titanic

- **Ticket: (character)**
    Numero de tiquete del pasajero

- **Fare: (numeric)**
    Tarifa del tiquete

- **Cabin: (character)**
    Numero de cabina

- **Embarked: (character)**
    Puerto de Embarque
    
### Fichero: Limpieza y anlaisis de datos/final_dataset.csv

Archivo con los datos finales analizados y utilizados en la práctica. con dos variables nuevas **AgeGroup** y **Family** de timo numericas.
