# Programacion_I
Materia de la Maestría en Ciencia de Datos

## Contenido del repositorio
* En el repositorio principal se encuentran las 7 lecciones revisadas en clase con sus respectivos ejercicios y tareas (numeradas del 1 al 7)
* En el repositorio "Challenges" se encuentran los 9 retos de programación
* En el repositorio "ChallengeFinal" se encuentra el código del reto final y su archivos resultantes (informe y nube de palabras)

### Descripción del Challenge Final
* Este código análiza libros de dominio público del sitio web https://www.gutenberg.org/
* Como información de entrada el usuario debe proporcionar un URL válido para el libro que se quiera analizar (por ejemplo: https://www.gutenberg.org/files/2000/2000-0.txt)
* El código está optimizado para el idioma español, por lo que se recomienda análizar libros en este idioma para obtener mejores resultados
* Los resultados del análisis se muestran en dos archivos separados, que contienen lo siguiente:
    1. nube_de_palabras.png - Una imagen que muestra las palabras más reelevantes sobre el libro, esta imagen no considera stopwords con la finalidad de que refleje el contenido del libro
    2. resultados.txt - URL analizado, cantidad de palabras únicas, las 5 palabras más comunes y su conteo, y la frecuencia de cada palabra en el texto