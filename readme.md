# Prueba Técnica Inventures  -  Cristóbal Domínguez

En resumen, el desarrollo de la tarea se aborda generando una clusterización de los puntos cercanos, en primer lugar por latitud y luego por distancia para obtener grupos de puntos cercanos y agruparlos para formar los nodes del grafo. De esta manera se obtiene un grafo conexo sobre el cual se utilza un algoritmo para encontrar los caminos mas cortos entre sus nodos.

La clusterización se hace de esta manera para evitar una comparación de distancia con todos los puntos del grafo (O(n^2)).

