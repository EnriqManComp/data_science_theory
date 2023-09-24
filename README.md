# Tipos de problemas en Ciencia de Datos
Existen muchos algoritmos en la ciencia de datos, pero relativamente pocos tipos de problemas
Principalmente existen 9 tipos de problemas
## Classification problem
No es más que clasificar en grupos a un conjunto de datos o entidades.
Un ejemplo es una compañía de servicios telefónicos que está interesada en saber quién está a punto de cancelar su servicio. Con esta información la compañía puede ofrecerle a estos individuos buenos tratos para mantenerlos como clientes. En este caso los posibles grupos serían: Muy probable que cancele y No es probable que cancele.
## Regression problem
Básicamente, se trata de predecir el valor de alguna variable basado en los valores de otros atributos que se conocen.
Un ejemplo es cuando se trata de predecir el valor de una casa por su área, localización, comparación con otras casas, etc.
## Similarity Matching
Se trata de identificar elementos similares en un dataset y usarlos para encontrar otros elementos similares fuera del dataset.
Se utiliza específicamente Similarity Matching en vez de Classification cuando las características que se tienen están un poco menos definidas que como se tienen en los problemas de calsificación.
Un ejemplo es dado un perfil de clientes satisfechos en una compañía y sus datos se necesita encontrar otros clientes potenciales que vayan a estar satisfechos ( sean clientes ya de la compañía o no ). Esto se realiza para enfocar los esfuerzos de marketing en este grupo de posibles clientes satisfechos.
## Clustering
Se trata de encontrar un orden natural de agrupar datos que no están etiquetados en un dataset.
Un ejemplo son las preferencias de música. Las preferencias pueden ser los géneros típicos: rock, pop, rap, etc. Pero también van surgiendo otros géneros que involucran parte de varios géneros. Y un modelo debe aprender que de las características de los audios de las canciones que se vayan escuchando es muy probable que le vaya a gustar tal canción o tal artista que está en el mismo cluster pero es de un género que nunca se había escuchado antes.
## Co-Occurrence Grouping
Encontrar elementos que ocurren juntos frecuentemente. Es conocido también como Market Basket Analysis.
Un ejemplo es un supermercado que encontró que algunas personas que compran carne generalmente también compran salsa. Este patrón lo que le permite al supermercado es poner estos dos elementos juntos sea para vender más o para comodidad del cliente. Un ejemplo en la práctica es el sistema de recomendado de Amazon.
## Profiling or Behavior Description
Define un comportamiento típico de un grupo de individuos.
Esto es usado por ejemplo en la detección de fraude de tarjetas de crédito. Si tienes una tarjeta de crédito que generalmente la usas en comprar artículos en tu región geográfica y repentinamente se compra un artículo en otro país la compañía de la tarjeta de crédito dirá este perfil realizó algo inusual y le pondrá una etiqueta y empezará a realizar la verificación si realmente su cliente realizó esta compra o no.
## Link Prediction
Se utiliza para predecir conexiones y fuerza de las mismas entre los elementos de los datos.
El ejemplo más concreto es Facebook, el cual recomienda amigos con los cuales piensa que tendrás una fuerte conexión basado en los datos de ambos pero en realidad no son amigos aún.
## Data Reduction
Lo que se persigue en este tipo de problema es tomar una gran cantidad de datos y reducir su dimensionalidad sin perder los aspectos importantes de estos.
Una analogía es la compresión de archivos donde se reduce el tamaño y luego lo podemos descomprimir y no se pierden los datos se conservan tal y como estaban anteriormente.
## Causal Modeling
El objetivo aquí es identificar causas y efectos en un dataset. Los demás tipos de problemas no tienen en cuenta estos dos aspectos solo implican correlación.
Por ejemplo si tomamos en consideración el ejemplo del problema de clasificación se tiene un modelo que realiza una clasificación binaria de clientes que tienen probabilidad alta de cancelar o no sus servicios pero no se identifica que en realidad 50 clientes causaron que fuera más probable que los demás cancelaran sus servicios.









