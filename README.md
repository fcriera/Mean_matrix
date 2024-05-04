"# Mean_matrix" 
Función process_matrix
Recibe como parámetro una matriz (lista de listas) de números y devuelve otra, con el mismo
tamaño y número de elementos.
process_matrix transforma los elementos de la matriz original.
Transformación
La transformación que aplica es la siguiente: cada elemento de la matriz pasa a tener como
valor el promedio de su valor antiguo y los valores de sus vecinos.
Los elementos que están en el interior, tienen 4 vecinos. Son el caso general.
Los elementos que se encuentran en el borde, tienen 3 vecinos. Son una excepción
Los elementos que se encuentran en las esquinas, tienen 2 vecinos. Son otra
excepción.