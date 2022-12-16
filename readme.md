# <h1 align="center">**`Proyecto Individual 2`**
# <h1 align="center">**Nicolás Lira Moreno**

**Introducción**

La hospitalización, o estancia hospitalaria, cuando es prolongada constituye una preocupación a nivel mundial debido a sus efectos negativos en el sistema de salud, aumentando los costos, generando deficiencia en la accesibilidad de prestación de servicios de salud, saturación de unidades de hospitalización y urgencias, por consiguiente, mayores efectos adversos como lo son las enfermedades intrahospitalarias.

**Problemática**

Un importante Centro de Salud lo ha contratado con el fin de poder predecir si un paciente tendrá una estancia hospitalaria prolongada o no, utilizando la información contenida en el dataset asociado, la cual recaba una muestra histórica de sus pacientes, para poder administrar la demanda de camas en el hospital según la condición de los pacientes recientemente ingresados.
Para esto, se define que un paciente posee estancia hospitalaria prolongada si ha estado hospitalizado más de 8 días.

**Metodología de trabajo**

- Se realizó un análisis exploratorio de los datos (EDA).
- Se dropearon las columnas 'innecesarias' (se explica en los comentarios del código) y se convierte los datos categóricos en valores numéricos.
- Se analiza la correlación con la columna 'prediccion' y dropean columnas 'innecesarias'
- Se divide el dataset en train y test utilizando train_test_split.
- Se realiza el entrenamiento y predicción utilizando "Regresión Logística".
- Se mide el 'recall' y 'accuracy' a través de la 'matriz de confusión'
- Se importa el dataset de 'test' para validar nuestro modelo de predicción y se efectúan los 3 primeros pasos.
- Se hacen comentarios y redacta con fundamentos la solución propuesta.
- Por último se genera un archivo para subirlo al repositorio.

**Conclusión**

Cambiando las variables del modelo de entrenamiento se ve que los valores de 'recall' y 'accuracy' se mantienen alrededor de 0,8 y 0,65, por lo que podemos concluir que es un modelo estable (no muy variable) pero no muy preciso. Aunque, al final del día cumple con su objetivo: predecir un evento.