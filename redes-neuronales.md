# Definición de una red neuronal

Una red neuronal es un modelo computacional inspirado por la estructura y funcionamiento del cerebro humano. Consiste de unidades de procesamiento interconectadas llamadas neuronas, las cuales se organizan en capas. La información fluye a través de esas capas, con cada neurona realizando una simple operación matemática con sus entradas y pasando el resultado a la siguiente capa. Las conexiones entre las neuronas son representadas por pesos (weights), los cuales determinan la fuerza y significado de las conexiones.

Las redes neuronales se usan típicamente para tareas como reconocimiento de patrones, clasificación, regresión y decisiones basadas en las entradas de información. Las redes neuronales aprenden por medio de ejemplos ajustando los pesos entre las neuronas por un proceso llamado entrenamiento, el cual involucra alimentar la red con datos de entrada y comparando sus salidas con la salida deseada. La red después actualiza sus pesos para minimizar las diferencias entre las salidas predecidas y las salidas deseadas, usando algoritmos como propagación hacia atrás (backpropagation).

# Ejemplos de redes neuronales

- ### Clasificación de imágenes
Las redes neuronales pueden ser entrenadas para clasificar imágenes, como reconocimiento de manuscritos, identificar objetos en fotos o imágenes o distinguir animales de entre varias imágenes parecidas.


- ### Procesamiento de lenguaje natural
Las redes neuronales se utilizan en tareas relacionadas al entendimiento y generación de lenguaje natural. Por ejemplo, en análisis de sentimiento, traducción automática, chatbots, resumir textos y reconocimiento del habla.

- ### Vehículos autónomos.
Las redes neuronales juegan un gran papel en permitir la navegación automática en automóviles. Procesan la información de los sensores, como imágenes de las cámaras o lecturas de radares y LiDAR (detección y medición de la luz) para percibir el ambiente, detectar objetos y hacer decisiones para navegar, acelerar y frenar

- ### Detección de fraude
Las redes neuronales se utilizan en detección de fraudes en varios dominios, como transacciones con tarjetas de crédito, reclamo de seguros, o banca en línea. Aprenden a identificar patrones y anomalías en la información que indica una actividad fraudulenta potencial.

- ### Recomendar sistemas.
Muchas plataformas en línea utilizan redes neuronales para construir sistemas de recomendación personal. Esos sistemas analizan el comportamiento y preferencias del usuario para sugerir productos relevantes, películas, música, o artículos.

# Esquema general de las matemáticas involucradas en redes neuronales
![Diagrama de flujo matematicas en redes neuronales](redes_neuronales_math.drawio.png)

# Problema de interés
![neural machine translation](https://www.transifex.com/wp-content/uploads/2022/08/Neural-Machine-Translation-featured.png)
Me interesa poder realizar traducciones por medio de redes neuronales.
En primera instancia elegiría el procesamiento de texto en un contexto en específico para que las traducciones sean coherentes y sean de utilidad.

- El lenguaje de traducción sería de inglés a español.
- El contexto sería desarrollo de software.

La justificación del por qué traducciones es porque la gran mayoría de la documentación relacionada al desarrollo de software está en inglés; mientras que la información que se encuentra en español es limitada o desactualizada. A pesar de que es cada vez más accesible la traducción por medio de varias herramientas o incluso personas y/o equipos se encargan de esa tarea, aún se requiere un esfuerzo adicional para que las traducciones sean precisas.
