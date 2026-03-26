# Práctica implementación y análisis de un sistema de recomendación basado en modelos
## Objetivo

Implementar un filtro colaborativo basado en factorización matricial de bajo rango (se puede utilizar el algoritmo SVD de Surprise). Además, realizarán actividades complementarias para profundizar en la interpretación, evaluación y aplicación de los modelos de recomendación.

## Instrucciones

1. Implementación básica del filtro colaborativo. Utilizar el dataset de ratings de MovieLens de 100k ratings (recommended for education and development, small)
2. Añadir uno o varios usuarios que representen a los miembros del equipo de prácticas (con ratings a un subconjunto de las películas del dataset), ajustar el filtro y mostrar las 10 mejores recomendaciones que proporciona a cada usuario añadido.
3. Analizar los sesgos estimados en el modelo ¿Qué usuarios tienden a puntuar más bajo o más alto? ¿Qué películas tienden a tener más ratings?
4. Análisis en el espacio latente a partir de los vectores de características latentes de usuarios y películas. Calcular las 10 películas más próximas a una dada, por ejemplo, “Toy Story”
5. Utilizar alguna técnica de clustering para obtener grupos de usuarios similares que pueden ser interpretados como segmentos de clientes

## Entregable

El alumno o grupo debe entregar un notebook perfectamente documentado donde se responda a las tareas propuestas.

## Evaluación y temporalización

La fecha límite de entrega coincide con la del cuestionario. Las entregas realizadas después de esta fecha tendrán una penalización del 30% en la calificación.

## Referencias
Movielens dataset https://grouplens.org/datasets/movielens/

Matrix Factorization-based algorithms (Surprise) https://surprise.readthedocs.io/en/stable/matrix_factorization.html#surprise.prediction_algorithms.matrix_factorization.SVD

