#### PARA EJECUTAR EL PROYECTO EN TOUCH HACE FALTA UN ARCHIVO DE MEDIAPIPE QUE PESA 100MB Y GITHUB NO DEJA PUSHEAR, ESCRIBEME POR TEAMS Y TE LO PASO JAJA :) 


# BITÁCORA PROYECTO FINAL VISION ARTIFICIAL

### Ideación

Para esta primera etapa decidimos vincular, 

**La pieza musical elegida** : La canción se llama [Ramalama (Bang Bang)](https://www.youtube.com/watch?v=YuGe533mWiA&t=4s), es una canción que escogimos porque sentimos que tenía mucha personalidad y además nos daba muchas vibes de [Halloween/brujas](https://www.youtube.com/watch?v=9RNQ_kl-gBk&list=RD9RNQ_kl-gBk&start_radio=1) , puedes clic al link para comprender mejor las sensaciones de la canción ya que la artista tiene una puesta en escena que visualmente representa muy bien a la pista sonora y queriamos lograr algo muy similar pero con cosas abstractas y simbólicas, así que nos pareció perfecta para la ocasión (estamos en el MOOD). 

**La descripción de nuestro concepto visual** : visualmente lo teniamos claro: representar un **Aquelarre de Brujas**. Los conceptos clave para las visuales era una congregación de objetos, movimientos en circulos para dar sensación de que algo está pasando entre esas formas/figuras. Finalmente integrar un resultado del Aquelarre: la hechicería, un conjuro, una maldición o algo así. 

**Los inputs seleccionados** :  

- La música, es uno de los principales modificadores de las formas (colores, tamaños y movimientos) que aparte de ser un requisito para esta entrega, es una manera de dinamizar los visuales ya que la musica tiene diferentes momentos que se pueden transmitir como input. 
- Modelo MediaPipe de visión artificial, decidimos integrarlo para darle más dinámica al papel de VJ, estamos convencidos de que esta técnica puede ser muy revolucionaria y decidimos utilizarla en conjunto de la materia de simulación para hacer esa convergencia entre ambas materias, que a nuestro parecer se complementan muy bien.


**4. ¿Qué algoritmos o técnicas planeas usar (ej: flow fields, flocking, física, partículas, etc.) y por qué?**

Para este proyecto utilizamos la física integrada al movimientos de nuestras formas y elementos de los visuales y además un sistema de particulas para representar esos hechizos/conjuros que serán el resultado del aquelarre, nos parece perfecto este efecto de "particulas flotantes" para dar esa sensación de MAGIA y fantasia. 

<img width="1128" height="362" alt="image" src="https://github.com/user-attachments/assets/18712e28-b1be-4585-8962-3a789708142e" />


# PROCESO

Para hacer nuestro proyecto final hicimos una asociación entre Sebas Torres y Manu Buriticá, con el objetivo de utilizar un nuevo programa que desconociamos llamado TouchDesigner pero con el que definitivamente queriamos experimentar. 

Para empezar hicimos un proceso de ideación en cuanto  a los efectos que queríamos hacer para llegar al concepto visual que creamos en conjunto.

Luego, empezamos nuestro proceso de experimentación/replicación de tutoriales que ya existen en YouTube con el fin de comprender cómo utilizar el programa y dominarlo más. Despues de esa indagación y práctica de manejos básicos de Touch iniciamos la experimentación que nos llevó a resultados muy diferentes y únicos. 

Seguido a esto, empezamos a ver documentación y tutoriales acerca de visuales Audioreactivos que nos ayudarian luego para implementarlo en nuestro modelo. 

En el proceso de hacer funcionar el mediaPipe con los visuales tuvimos varios problemas para usar el plugging porque del repositorio de donde lo adquirimos no tenía actualizado el plugging y hacerlo funcionar fue un dolor de cabeza. Para solucionarlo tuvimos que sacar un gran pedazo de tiempo en ver tutoriales y leer la documentación de Torin para descubrir que pasaba, la solución fue sencilla: buscar una de las versiones más recientes del plugging que tenia mejores acabado y precisiones. Finalmente lo hicimos y terminamos definiendo que parámetro iba a controlar cada valor obtenido tanto del MediaPipe como del audio análisis (del cual usamos low,high,snare,kick).

<img width="752" height="715" alt="image" src="https://github.com/user-attachments/assets/79fd76f6-be33-4f97-a2f0-8850e7b571ac" />
