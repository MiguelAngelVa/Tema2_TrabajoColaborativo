# Tema2_TrabajoColaborativo
Carlos Andres Giraldo Saldarriaga

Maria Victoria Valencia Arango

## Historia y ciclo de vida de una aplicación de Aprendizaje de Máquina

Se describirán a continuación las etapas o fases del ciclo de vida para aplicaciones de aprendizaje de máquinas.

1. Identificación del problema
2. Recolección de datos
3. Preparación de datos
4. Ingeniería de modelos
5. Evaluación del modelo
6. Despliegue
7. Mantenimiento y actualización

De acuerdo con las etapas mencionadas, se debe tener en cuenta que para iniciar a desarrollar, es importante conocer el reto a resolver, tener claridad del contexto del problema y de esta manera avanzar con las demás etapas donde se encuentran involucrados los datos: recolección, proceso de limpieza y calidad de datos para posteriormente iniciar el modelado analítico de acuerdo a la necesidad del negocio.

Adicionalmente, se requiere hacer una evaluación del modelo para evidenciar posibles mejoras y posteriormente hacer los despliegues correspondientes para los pasos a producción.

Los diferentes tipos de aprendizaje de máquina son los siguientes:

- Ciencia de datos, Matemáticas, Probabilidad estadística.
- Algoritmos de agrupación.
- Redes neuronales.
    * Aprendizaje profundo.
- Algoritmos bayesianos.
- Algoritmos de regresión.
- Árboles de decisión.


<img src="AI1.png" alt="Capas IA" width="400" height="300">

## Preparación de datos

- Análisis exploratorio de los datos: Conocer la tipología y cómo llegan los datos de la fuente.
    * Evaluación de nulos.
    * Datos faltantes.
    * Duplicidad.
    * Tipos de datos.
- Limpieza de datos: Se busca organizar la data para evitar fallos en los modelos analíticos posteriores.

Existen diferentes tipos de análisis:

- Exploratorio
- Descriptivo
- Relacional
- Explicativo
- Predictivo

<img src="tipo_datos.png" alt="tipo datos" width="400" height="300">

## Analítica de datos

Una vez se tienen los datos limpios y de calidad, se procede a tener conjuntos de entrenamiento y prueba de acuerdo a los modelos que vamos a utilizar.
Esto permitirá al modelo aprender sobre los datos y posteriormente hacer testeo sobre ellos.
Para estos conjuntos de entrenamientos se pueden tomar porciones de datos 70% para entrenamiento y 30% para testeo, ó tomar 80% para entrenamiento y 20% para testeo.

<img src="sets.png" alt="sets" width="400" height="100">


- Selección de modelo
    * Supervisado
        * Clasificación
        * Regresión
    * No supervisado
        * Agrupaciones (clustering)



Paula Rocio Jacobo Marin

Daniel Calle Pulgarin
Ciclo de vida 
El desarrollo de una aplicación de aprendizaje de máquina sigue un ciclo de vida estructurado que asegura que el modelo sea efectivo, preciso y útil. Esto se lleva a cabo por medio de unas etapas o fases :
Machine learning 
Machine Learning representa un nuevo paradigma en la programación, donde en lugar de programar reglas explícitas en un lenguaje como Java o C ++, se entrena un sistema con datos para inferir las reglas por sí mismo.
Identificación del problema
El primer paso en el ciclo de vida de una aplicación de aprendizaje automático es identificar el problema que se quiere resolver. Esto significa definir claramente el objetivo del proyecto y determinar de qué manera el aprendizaje automático puede ayudar a lograrlo.
Recolección de datos 
Después de identificar el problema, el siguiente paso es recopilar datos. Estos datos se usarán para entrenar el modelo. Es crucial que los datos sean relevantes, precisos y representen bien el problema que se quiere solucionar.
Preparación de datos
Los datos en bruto casi nunca están listos para ser utilizados directamente en el entrenamiento del modelo. La fase de preparación de datos consiste en limpiar los datos, gestionar los valores faltantes, normalizar y escalar las características, y dividirlos en conjuntos de entrenamiento y prueba.
Ingeniería de modelos
En esta etapa, se eligen y entrenan los modelos de aprendizaje automático con los datos ya preparados. Esto incluye seleccionar los algoritmos, realizar ingeniería de características (feature engineering) y ajustar los hiperparámetros para optimizar el rendimiento del modelo.
Evaluación del modelo
Después de entrenar el modelo, es fundamental evaluar su desempeño. Esto se hace midiendo métricas como la precisión, exactitud, recall y F1-score, utilizando el conjunto de prueba. La evaluación permite verificar si el modelo es lo suficientemente bueno para ser implementado.

¿Cómo seleccionar el mejor modelo en un problema de machine learning?
1. Definir el problema y las métricas de evaluación
•	Antes de seleccionar un modelo, es crucial definir el tipo de problema (clasificación, regresión, etc.) y las métricas adecuadas para evaluarlo. Las métricas comunes incluyen:
o	Precisión (Accuracy): Qué tan bien el modelo clasifica correctamente.
o	Recall: Qué porcentaje de los casos positivos son detectados correctamente.
o	F1-Score: El balance entre precisión y recall.
o	MSE (Mean Squared Error): Usada para regresión.
o	AUC-ROC: Para medir el rendimiento en clasificación binaria.
2. Seleccionar un conjunto de modelos candidatos
•	Elige varios modelos que puedan ser adecuados para tu problema, como:
o	Regresión lineal o logística
o	Árboles de decisión
o	Random Forest
o	Gradient Boosting Machines (GBM)
o	Redes neuronales
o	SVM (Máquinas de Soporte Vectorial)
3. Dividir los datos en conjuntos de entrenamiento y prueba
•	Usa una parte de los datos para entrenar y otra para probar el rendimiento de los modelos. A menudo, se utiliza una división 80-20 o 70-30.
4. Entrenar y ajustar los modelos
•	Entrena cada modelo con el conjunto de entrenamiento y realiza ajustes de hiperparámetros usando técnicas como:
o	Búsqueda en cuadrícula (Grid Search) o Búsqueda aleatoria (Random Search).
o	Validación cruzada (Cross-Validation): Divide los datos en varios subconjuntos para asegurar que el modelo generaliza bien.
5. Comparar el rendimiento en el conjunto de prueba
•	Evalúa el rendimiento de cada modelo usando las métricas definidas y compara los resultados. El modelo con mejor rendimiento en la métrica más relevante será el mejor candidato.
6. Evitar el sobreajuste
•	Asegúrate de que el modelo no esté sobreajustado a los datos de entrenamiento, lo que podría dar un alto rendimiento en entrenamiento pero pobre en prueba. Esto se puede verificar revisando si hay una gran diferencia entre el rendimiento en el entrenamiento y el de prueba.
7. Interpretabilidad vs. Complejidad
•	A veces, el mejor modelo no solo es el más preciso, sino también el más fácil de interpretar. Modelos como regresión lineal o árboles de decisión son más simples de interpretar en comparación con redes neuronales profundas.
8. Pruebas adicionales o validación externa
•	Si es posible, valida el modelo en un conjunto de datos externos que no se usaron en el entrenamiento para verificar que funcione bien en datos nuevos.
9. Seleccionar el modelo con mejor equilibrio
•	El mejor modelo será el que tenga el mejor rendimiento en las métricas clave, que no esté sobreajustado y que sea lo suficientemente interpretable y eficiente para el propósito del proyecto.
Despliegue 
Desplegar el modelo significa ponerlo en funcionamiento en un entorno real para que pueda ser utilizado. Esto puede requerir integrar el modelo en aplicaciones ya existentes, crear APIs para que otras aplicaciones interactúen con él, y configurar la infraestructura necesaria para gestionar las predicciones en tiempo real.
Mantenimiento y actualización 
El ciclo de vida de una aplicación de aprendizaje automático no finaliza con el despliegue. Es crucial monitorear el rendimiento del modelo en producción y realizar actualizaciones periódicas para asegurar su precisión y relevancia. Esto puede incluir reentrenar el modelo con nuevos datos o ajustar sus parámetros según sea necesario.


*******************************************************************
#Jaime Andrés Londoño Acevedo
##Introduccion Machine Learning
- Programación Lineal: Entradas Datos y Reglas. Salida: Resultado
- Machine Learning: Entradas Respuestas y Datos. Salida: Reglas

###Fases:
1 Identificación del problema: Definir el objetivo del proyecto y como el aprendizaje de máquina puede ayudar a alcanzarlo.
2 Recolección de datos: Datos relevantes, precisos y representativos del problema.
3 Preparación de datos: Lmpiar datos, manejar valores faltantes, normalizar, escalar caracteristicas, dividir en conjuntos.
4 Ingenieria de modelos: Selección de algoritmos, feature engineering, ajustes hiperparámetros. 
5 Evaluación del modelo: Medir precisión, exactitud, recall, F1-score.
   Parámetros: Variables numéricas internas que el modelo aprende
   Hiperparámetros: Variables numércias externas que nosotros debemos fijar al momento de hacer el algoritmo.
6 Despliegue: Ponerlo en producción, integrarlo con aplicaciones.
   Requerimientos de diseño: Tipo de predicción (Tiempo real o por lotes), latencia, rendimiento (numero solicitudes por segundo)
   Alternativas de despliegue: En la nube, on the edge.
7 Mantenimiento y actualización: Monitoreo, actualizaciones periódicas, ajustar parámetros.
   Fallos de software: Código para despliegue por ejemplo
   Fallos en el modelo: Deriva de datos, Deriva de concepto.
   Monitoreo con métricas globales.
   Distribuciones estadísticas.
******************************************************************
Ximena Perez Burgos

Wilmer Jamioy Tisoy 

Jhoksser Fernando Mejía Ramos

Victor Alfonso Gutierrez Lopez

Maritza Cristina Parra Jimenez

Robinson Loaiza Davila

Claudia Lorena Ramírez Franco

Roberto Alejandro Sánchez

Claudia Cardenas

Luis Angel Montoya Suárez 

Yessica Marcela Triana Cordoba

Luis Fernando Meneses Caviedes

Tema 2 - Historia y Ciclo de Vida de una Aplicación de Aprendizaje de Máquina

El desarrollo de una aplicación de aprendizaje de máquina sigue un ciclo de vida estructurado que asegura que el modelo sea efectivo, preciso y útil. Cada etapa de este ciclo es crucial para el éxito del proyecto. A continuación, se describen las fases típicas en el ciclo de vida de una aplicación de aprendizaje de máquina, junto con ejemplos que ilustran cada paso.

Introducción a Machine Learning (ML Zero to Hero, parte 1)
Machine Learning representa un nuevo paradigma en la programación, donde en lugar de programar reglas explícitas en un lenguaje como Java o C ++, se entrena un sistema con datos para inferir las reglas por sí mismo. Pero ¿cómo es en realidad el ML?
VIEW ON YouTube

El Machine Learning es el camino a la IA, aquí aplicaremos el lenguaje Phyton, cuando se trata de programación tradición se aplican Reglas para procesar los datos y asi obtener un resultado, en Machine Learning invertimos los papeles y en lugar de brindarle las reglas le damos los resultados o los datos para obtener las reglas


Sebastian de Jesus Garcia Lopez

Valentina Cepeda Duque

Juan Diego Araque Muñoz

José Luis Cardeño Tejada

Geovanny Vergara Ramírez 

Carlos Perea

Juan Pablo Guzmán Moreno

Maria Camila Castro Isa

Diana Carolina Arias Valencia

Edisson Ferley Echavarria Marin

Diana Maribel Balaguera Arroyave

Sebastian Castañeda Garcia

Carlos Bolaños
