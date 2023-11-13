# Schedule_Maker
Este repositorio tiene un archivo que busca recomendaciones de profesores en [https://foroupiicsa.net/diccionario/buscar/] sin tener que andar poniendo el nombre del profesor uno por uno 

### La salida tiene 

**Comentario:** 
**Materia:** 
**Fecha:** 


Este repositorio tiene un directorio llamado HORARIO_MAKER donde tien un archivo en jupiternotebook llamado Find.ipynb y otro directorio llamado data 

## Como usarlo?

1. Guarda el nombre de los profesores de los que quieres obtener referencias en un archivo .csv(lo mas sensillo es copiar los nombres Desde el SAES en el apartado de los horarios y pegarlos en un excel, para despues darle guardar como csv) e introducelo en el directorio llamado "data"
2. Ahora dentro del archivo llamado Find.ipynb remplaza en ruta_archivo_csv(que esta despues de los imports) el path de tu archivo .csv que tiene los nombres de los profesores
3. Corre el jupyternotebook completo con el boton Run all

## CASOS A TENER EN CUENTA 

1. Si se presenta un error despues de correr el codigo es posible que en el archivo .csv algun nombre de un profesor tenga algun simbolo como un punto "." o tenga abrebiaciones como Lic o Doc habra que removerlos
2. En el codigo esta integrada una libreria en la cual se puede leer el sentimiento de lo que dice el comentario respecto al profesor, esta libreria suelta una calificacion entre mas alta mejor, pero tiene un fallo ya que no funciona correctamente con el idioma español asi que la puntuacion puede tener un sesgo, ejemplo de como podria ser un sesgo:

(Promedio de puntuaciones: -0.2939
****CALIFICACION GENERAL****: Extremadamente negativo)

   
