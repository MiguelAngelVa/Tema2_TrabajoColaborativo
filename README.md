# Tema2_TrabajoColaborativo
Carlos Andres Giraldo Saldarriaga
Fases Típicas del ciclo de vida del Aprendizaje de Máquina
1. Identificación del problema:
Definir claramente el objetivo del proyecto y determinar como el aprendizaje de máquina puede ayudar a alcanzar el objetivo.

2. Recolección de datos:
Una vez identificado el problema, la siguiente fase es la recolección de datos, estos datos serán utilizados para entrenar el modelo. Es importante asegurarse de que los datos sean relevantes, precisos y representativos del problema que se está tratando de resolver.

3. Preparación de los datos:
Los datos crudos raramente están listos para ser usados directamente para el modelo. La preparación de datos implica limpiar los datos, manejar los valores faltantes, normalizar y escalar las caracteristicas y dividir los datos en conjunto de entrenamiento y prueba.

4. Ingeniería de datos:
En esta fase, se seleccionan y entrenan modelos de aprendizaje de maquina, utilizando datos preparados. Esta etapa puede incluir la selección de algoritmos, la creacion de caracteristica (featuring engeniering), y la realización de ajustes de hiperparametros para optimizar el rendimiento del modelo.

5. Evaluación del modelo:
Una vez el modelo ha sido entrenado, es crucial evaluar su desempeño. Esto implica medir la precision, , la exactitud, el recall, la F1-score, entre otras metricas, usando el conjunto de prueba. La evaluación ayuda a determinar si el modelo es suficientemente bueno para ser desplegado.

6. Desplieque:
Desplegar el modelo significa ponerlo en producción para que pueda ser utiliado en un entorno real. Esto puede implicar la integración del modelo en aplicaciones existentes, la creación de API´s y la configuración de infraestructura para manejar las predicciones en tiempo real.

7. Mantenimiento y actualización:
El ciclo de vida de una aplicacion no termina en el despliugue. Es importante monitorear el desempeño del modelo en producción y realizar actualizaciones periodicas para mantener su precisión y relevancia. Estoa puede implicar reentrenar el modelo con nuevos datos o ajustar sus parametros.
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
# Tema 2 Historia y Ciclo de Vida de una Aplicación de Aprendizaje de Máquina
## Por: Jaime Londoño

### Introduccion Machine Learning
- Programación Lineal: Entradas Datos y Reglas. Salida: Resultado
- Machine Learning: Entradas Respuestas y Datos. Salida: Reglas

#### Fases:
1 Identificación del problema: Definir el objetivo del proyecto y como el aprendizaje de máquina puede ayudar a alcanzarlo.
2 Recolección de datos: Datos relevantes, precisos y representativos del problema.
3 Preparación de datos: Lmpiar datos, manejar valores faltantes, normalizar, escalar caracteristicas, dividir en conjuntos.
4 Ingenieria de modelos: Selección de algoritmos, feature engineering, ajustes hiperparámetros. 
5 Evaluación del modelo: Medir precisión, exactitud, recall, F1-score.

   Parámetros: Variables numéricas internas que el modelo aprende
   Hiperparámetros: Variables numércias externas que nosotros debemos fijar al momento de hacer el algoritmo.

6 Despliegue: Ponerlo en producción, integrarlo con aplicaciones.

   Requerimientos de diseño: Tipo de predicción (Tiempo real o por lotes), latencia, rendimiento (numero solicit  udes por segundo)
   Alternativas de despliegue: En la nube, on the edge.

7 Mantenimiento y actualización: Monitoreo, actualizaciones periódicas, ajustar parámetros.

   Fallos de software: Código para despliegue por ejemplo
   Fallos en el modelo: Deriva de datos, Deriva de concepto.
   Monitoreo con métricas globales.
   Distribuciones estadísticas.

#### HISTORIA
- Arthur Samuel (1959), disciplina que estudia habilidad de aprendizaje de computadores.
- Tom Mitchel (1998), aprendizaje computacional.
- 1950 Artificial Intelligence, 1980 Machine Learing, 2010 Deep Learning.

Medicina: Reconocimiento de imagenes con cáncer.
Políticas publicas: predicción de riesgo (delitos, violencia, etc.)
Fiscalización: detección de fraude.
Manufactura: predicción de fallas
Agricultura: identificación de cultivos
Comercio: segmentación de clientes.

Sistemas Bioinspirados: Algoritmos genéticos, Algoritmos de enjambre, Redes Neuronales.

Aprendizaje supervisado: Clasificaciones (Arboles de decisión, Naive Bayes, XGB, Redes neuronales), Regresiones (Regresión lineal, Arbol de regresión, regresión Logística, Redes neuronales).

Aprendizaje no supervisado: Agrupaciones (Clustering).
******************************************************************
Ximena Perez Burgos

Wilmer Jamioy Tisoy 
# Tema 2 -Historia Ciclo de vida de una aplicación de Aprendizaje de máquina

Machine Learning representa un nuevo paradigma en la programación, donde en lugar de programar reglas explícitas en un lenguaje como Java o C ++, se entrena un sistema con datos para inferir las reglas por sí mismo.

## Pasos 

1. Identificación del Problema
2. Recolección de Datos
3. Preparación de Datos
4. Ingeniería de Modelos
5. Evaluación del Modelo
6. Despliegue
7. Mantenimiento y Actualización


Jhoksser Fernando Mejía Ramos

HISTORIA Y CICLO DE VIDA DE UNA APLICACIÓN DE APRENDIZAJE DE MÁQUINA 

el desarrollo de una aplicación sigue un ciclo de vida estructurado que lo hace efectivo, preciso y útil.

FASE 1. IDENTIFICACIÓN DEL PROBLEMA 
Identificar el problema que se quiere resolver, indicar claramente el objetivo del proyecto y determinar como el ML ayuda a resolver el problema
Ejemplo: predecir la demanda de un producto.

FASE 2. RECOLECCÍON DE DATOS 
Se recolectan datos para entrenar el modelo, estos datos deben ser relevantes, precisos y representativos del problema.
Ejemplo: recolectar datos hístoricos de ventas, de tendencia, busqueda en línea, datos de campañas pasadas.

FASE 3. PREPARACIÓN DE LOS DATOS
Los datos deben ser limpiados, manejar valores faltantes, normalizar y escalar características
Ejemplo: La empresa elimina datos duplicados, maneja valores faltantes, o normaliza los precios y cantidades vendidas


FASE 4. INGENIERÍA DE MODELOS.
Se selecciona el mejor modelo y se entrena con los datos ya preparados y se hacen los ajustes al modelo
Ejemplo: La empresa experimenta con varios algoritos de regresión y árboles de decisión para encontrar el mejor modelo.


FASE 5. EVALUACIÓN DEL MODELO.
en esta fase se evaluan el desempeño de los modelos y se escoje el mejor modelo segun la métrica que se quiere entrena. 
Ejemplo: La empresa usa modelos de metricas para determinar el mejor modelo para resolver su problema. Maquina de soporte vectorial, bosque aleatorio o red neuronal. usan RMSE

FASE 6. DESPLIEGUE
Significa poner el modelo en el mundo real, integrarlo a la infraestructura o aplicaciones existentes. Este despliegue puede ser en remoto o en la nube.
Ejemplo: La empresa despliega el modelo en su sistema de inventario, permitiendo predecir los pedidos o ventas.

FASE 7 MANTENIMIENTO Y ACTUALIZACIÓN
Es importante monitorear el desempeño del modelo y mantenerlo actualizado, los modelos pueden ser reentrenados para ajustar sus parametros
Ejemplo:La empresa monitorea el modelo y lo compara con las ventas reales y lo reentrena con nuevos datos para aprovechar al máximo el potencial del modelo

Victor Alfonso Gutierrez Lopez
Resumen: Historia y Ciclo de Vida de una Aplicación de Aprendizaje de Máquina
El ciclo de vida de una aplicación de aprendizaje de máquina sigue una serie de pasos estructurados para asegurar su efectividad y precisión.

Identificación del problema: Se define el objetivo que el aprendizaje de máquina puede ayudar a alcanzar. Ejemplo: predecir la demanda de productos en una tienda.

Recolección de datos: Se obtienen datos relevantes y precisos para entrenar el modelo. Ejemplo: datos históricos de ventas, tendencias de búsqueda, demografía y campañas de marketing.

Preparación de datos: Los datos se limpian, normalizan y dividen en conjuntos de entrenamiento y prueba. Ejemplo: eliminación de duplicados y manejo de valores faltantes.

Ingeniería de modelos: Se seleccionan y entrenan modelos, ajustando parámetros y creando características adicionales para optimizar resultados. Ejemplo: algoritmos de regresión y árboles de decisión.

Evaluación del modelo: Se evalúa el modelo usando métricas como el error cuadrático medio (MSE) para asegurarse de su efectividad antes de implementarlo.

Despliegue: El modelo se integra en el entorno de producción para hacer predicciones en tiempo real. Ejemplo: la predicción de demanda se usa para ajustar el inventario de una tienda.

Mantenimiento y actualización: Se monitorea y actualiza el modelo continuamente, reentrenándolo con nuevos datos para mantener su relevancia. Ejemplo: ajuste del modelo en base a datos de ventas reales.


Maritza Cristina Parra Jimenez

Robinson Loaiza Davila

# Historia y Ciclo de Vida de una Aplicación de Aprendizaje de Máquina

# Machine Learning
__Definicion:__ Enseñar a una computadora de la misma manera que se le enseña a un humano, 

__1. Identificación del Problema:__ Definir claramente el objetivo del proyecto y determinar cómo ML puede ayudar a alcanzar el objetivo.

__2. Recolección de los datos:__ Los datos serán utilizados para entrenar el modelo. Los datos deben ser relevantes, precisos y representativos.

__3. Preparación de los datos:__ Implica limpiar los datos, manejar los valores faltantes, normalizar, escalar las características, y dividir los datos en conjuntos de entrenamiento y prueba.

__4. Ingeniería de Modelos:__ Se entrenan modelos de aprendizaje de máquina utilizando los datos preparados. Esta etapa puede incluir la selección de algoritmos, la creación de características y la realización de ajustes de hiperparámetros para optimizar el rendimiento del modelo. (Algoritmos de regresión, y arboles de decisión).

__5. Evaluación del Modelo:__ Esto implica medir la precisión, la exactitud y otras métricas (Pruebas). Parámetros: Variables numéricas internas e Hiperparámetros son variables numéricas externas, afinación de hiperparámetros.

    •	Métricas de desempeño.
    •	Posibles arquitecturas o tipos de modelos más adecuados.
    •	Se entrena, se afina y se valida el modelo.
    •	Se elige el modelo con mejor métrica de desempeño.

__6 Despliegue:__ Llevarlo de una etapa de desarrollo a una etapa de producción para ser utilizado en un entorno real.

__7. Mantenimiento y Actualización:__  Después del despliegue es necesario monitorear el desempeño, realizar actualizaciones periódicas para mantener la precisión y relevancia.


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
las fases de un ciclo de vida de una aplicacion de aprendizaje de maquina son:

* Identificación del problema: Se define el objetivo del proyecto, determinando cómo el ML puede solucionar el problema identificado. Por ejemplo, una empresa podría querer predecir la demanda de productos para optimizar su inventario.

* Recolección de datos: Se recopilan datos relevantes que alimentarán el modelo, asegurando que sean representativos y de calidad. En nuestro ejemplo, la empresa recogería datos de ventas históricas, demografía y campañas de marketing.

* Preparación de datos: Los datos crudos se limpian y preparan para el entrenamiento. Esto incluye eliminar duplicados, manejar valores faltantes, normalizar características y dividir los datos en conjuntos de entrenamiento y prueba.

* Ingeniería de modelos: Se seleccionan y entrenan los modelos utilizando algoritmos adecuados. También se ajustan los hiperparámetros y se realizan mejoras en la representación de las características.

* Evaluación del modelo: El rendimiento del modelo se evalúa usando diversas métricas, como la precisión, exactitud y F1-score. Esto permite seleccionar el mejor modelo para resolver el problema.

* Despliegue: El modelo se integra en sistemas productivos, como una API o un sistema de gestión de inventario en tiempo real.

* Mantenimiento y actualización: El ciclo continúa después del despliegue. Se monitorea el rendimiento del modelo y, si es necesario, se actualiza o reentrena con nuevos datos.

Este ciclo de vida permite que los sistemas de ML se mantengan eficientes y alineados con los objetivos del negocio a lo largo del tiempo.

En resumen el ciclo de vida de una aplicación de aprendizaje de máquina comienza con la identificación del problema, donde se define el objetivo del proyecto. Luego se realiza la recolección de datos relevantes para alimentar el modelo. Después, los datos se preparan para el modelo mediante la limpieza y normalización. En la fase de ingeniería de modelos, se seleccionan algoritmos y se entrenan modelos que luego se evalúan. Una vez seleccionado el mejor modelo, se despliega en producción, y finalmente se realiza un mantenimiento continuo para asegurar su relevancia y precisión.



Valentina Cepeda Duque

Juan Diego Araque Muñoz

José Luis Cardeño Tejada

Geovanny Vergara Ramírez 
****
Historia y ciclo de vida de una aplicación de Aprendizaje de Máquina

El desarrollo de una aplicación de Aprendizaje de Máquina (Machine Learning) sigue un ciclo de vida compuesto por siete etapas principales:

1. Identificación del problema
2. Recolección de datos
3. Preparación de datos
4. Ingeniería de modelos
5. Evaluación del modelo
6. Despliegue
7. Mantenimiento y actualización

Para iniciar el desarrollo, es crucial comprender claramente el desafío a resolver y su contexto. Esto permite avanzar eficientemente en las etapas subsiguientes, que involucran el manejo de datos: recolección, limpieza y aseguramiento de calidad. Posteriormente, se procede al modelado analítico según las necesidades específicas del negocio.

Es esencial evaluar el modelo para identificar posibles mejoras antes de realizar los despliegues correspondientes en producción.

Tipos de Aprendizaje de Máquina:
- Ciencia de datos, Matemáticas, Probabilidad estadística
- Algoritmos de agrupación
- Redes neuronales (incluyendo Aprendizaje profundo)
- Algoritmos bayesianos
- Algoritmos de regresión
- Árboles de decisión

Preparación de datos:
1. Análisis exploratorio:
   - Evaluación de valores nulos
   - Identificación de datos faltantes
   - Detección de duplicados
   - Verificación de tipos de datos

2. Limpieza de datos: Organización para prevenir errores en modelos analíticos futuros

Tipos de análisis:
- Exploratorio
- Descriptivo
- Relacional
- Explicativo
- Predictivo

Analítica de datos:
Una vez que los datos están limpios y son de calidad, se crean conjuntos de entrenamiento y prueba. Comúnmente, se utilizan proporciones de 70/30 o 80/20 para entrenamiento y prueba, respectivamente.

Selección de modelo:
1. Supervisado:
   - Clasificación
   - Regresión
2. No supervisado:
   - Agrupaciones (clustering)

Este enfoque estructurado garantiza un desarrollo eficaz y eficiente de aplicaciones de Aprendizaje de Máquina, desde la conceptualización hasta la implementación y mantenimiento.

****

Carlos Perea

Juan Pablo Guzmán Moreno

###1. Entender el problema
Primero, tienes que saber bien cuál es el problema que quieres resolver con ia. ¿Qué necesitas mejorar o predecir usando los datos?

###2. Reunir y preparar los datos
Luego, debes buscar los datos necesarios para resolver el problema. Puede ser información de clientes, ventas, imágenes, etc.
Después, es importante limpiar esos datos: quitar errores, completar datos que faltan y organizarlos para que el modelo los entienda bien.

###3. Dividir los datos
Separas los datos en dos grupos: uno para entrenar el modelo y otro para probar qué tan bien funciona.
A veces también divides los datos en más partes para probar varias veces que el modelo funciona bien en diferentes escenarios.

###4. Elegir el modelo
Ahora, eliges qué tipo de modelo usar (hay muchos tipos, como los que predicen números o clasifican cosas en categorías).
Luego, entrenas el modelo con los datos para que "aprenda" a hacer predicciones.

###5. Evaluar el modelo
Cuando el modelo ya ha aprendido, lo pruebas para ver qué tan bien predice.
Si no lo hace bien, ajustas algunas configuraciones para mejorar los resultados.

###6. Ponerlo a funcionar
Una vez que el modelo está listo, lo integras en una aplicación o sistema real, para que pueda hacer predicciones en el día a día.
También necesitas vigilarlo para asegurarte de que sigue funcionando bien.

###7. Mantener y mejorar
Con el tiempo, los datos pueden cambiar o el modelo puede dejar de ser tan efectivo, así que es importante actualizarlo y entrenarlo de nuevo con datos más recientes.
Siempre puedes seguir mejorando el modelo para que sea más preciso.
Este proceso es cíclico, lo que significa que siempre puedes volver a pasos anteriores para mejorar el modelo o adaptarlo a nuevas necesidades.

Maria Camila Castro Isa

Diana Carolina Arias Valencia

Edisson Ferley Echavarria Marin

Diana Maribel Balaguera Arroyave

Sebastian Castañeda Garcia

Carlos Bolaños

Aurelio Cheveroni
El texto del resumen.
