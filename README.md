# Proyecto final Automatización y control - Estimador de diabetes
Integrantes del Proyecto:Diego Alejandro Melo, Jhon Sebastian Montenegro, Giovanni Javier Pantoja 


![Imagen1|](https://github.com/GiovanniPantoja12/Proyecto-final-Automatizaci-n-y-control/blob/c3480a8ede60a4f653d19cd9df0ad49f3a8d48fb/Imagenes/dest-prediabetes.jpg)

## Descripción

Este proyecto presenta un Estimador de Diabetes diseñado para ser intuitivo y accesible para usuarios no técnicos. Utilizando una interfaz de usuario desarrollada con Streamlit, el sistema automatiza la tarea de estimar la probabilidad de diabetes en función de diversas variables de salud. El Estimador de Diabetes utiliza un modelo de Random Forest entrenado con datos reales y/o regionales, donde la base de datos incluye variables cruciales como género, edad, hipertensión, enfermedad cardíaca, índice de masa corporal (BMI), nivel de hemoglobina A1c y nivel de glucosa en sangre. El objetivo principal de esta herramienta es ofrecer una solución práctica y útil para predecir la presencia de diabetes en individuos, promoviendo así la conciencia y el cuidado de la salud.

## Características Principales

- Interfaz de usuario intuitiva desarrollada con Streamlit.
- Modelo de Random Forest entrenado con la [base de datos](https://github.com/GiovanniPantoja12/Proyecto-final-Automatizaci-n-y-control/blob/6606ba163bcdecdb9089399ea656332d5b9a021b/Base%20de%20datos/Datos_Diabetes.db)  proporcionada por: https://www.kaggle.com/code/tumpanjawat/diabetes-eda-random-forest-hp.
  
  De igual manera, se hizo una adaptación de la misma con el fin de hacer que los datos tuvieran una mejor aprehencion por el modelo, pues el modelo que se usó (Random Forest) no es capaz de aprender con datos de tipo String/Objeto, por eso fue necesario convertirse a tipo Int y Real
- Base de datos incluye variables cruciales como género, edad, hipertensión, enfermedad cardíaca, índice de masa corporal (BMI), nivel de hemoglobina A1c y nivel de glucosa en sangre.
- Herramienta práctica y útil para predecir la presencia de diabetes en individuos.

## Instrucciones de uso

El proceso a seguir para poder ejecutar el modelo y con el fin de visualizar la app web creada mediante Streamlit es el siguiente:


- Primero, abra el notebook que encuentra en [Estimador diabetes](), de click en el encabezado, asi podrá abrir la pagina de Google Collab y ejecutar de manera mas simple el codigo.

Antes de poder ejecutar el codigo, por favor suba al proyecto, la siguiente base de datos  [Datos_Diabetes.db](https://github.com/GiovanniPantoja12/Proyecto-final-Automatizaci-n-y-control/blob/6606ba163bcdecdb9089399ea656332d5b9a021b/Base%20de%20datos/Datos_Diabetes.db), posteriormente ejecute con calma cada uno de los bloques de codigo

- Cuando haya ejecutado el ultimo bloque, obtendrá un numero separado por puntos, con este formato: 00.00.000.00. Copie este numero. 

- Posteriormente, abra el link que encuentra en el ultimo renglón, la web que se abre pedirá la clave que anterior mente copio, introdúzcala y espere hasta visualizar la web de predicción de diabetes.

- Rellene los campos con toda la información necesaria, hágalo con calma, deberá esperar que la pagina cargue después de cada modificación de dato, por ultimo, de click en DIAGNOSTICO y obtenga la prediccion
