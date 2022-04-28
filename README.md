# Curso-de-excel
Curso de excel básico - Platzi
## Introducción - Lo que aprenderás sobre excel
Profesora Beatriz Ibañez 

Lista de necesidades y comandos básicos en excel
![Lista de necesidades y comandos básicos en excel](https://github.com/otravalentina/Curso-de-excel/blob/main/IMG_0410.jpg)

## Clase 1 - Importar datos y crear un nuevo archivo
Descargar archivos de Kaggle - E-commerce public datasets Alibaba
[Dataset a trabajar](https://www.kaggle.com/datasets/AppleEcomerceInfo/ecommerce-information)

Se señala todo con la flecha que está en la parte izquierda superior de excel

![Resumen clase](https://github.com/otravalentina/Curso-de-excel/blob/main/Screen%20Shot%202022-03-31%20at%208.56.30%20PM.png) 

La ventaja de excel es que te va a permitir procesar la información, hacer cálculo y procesar los datos. 

![Reumen órdenes](https://github.com/otravalentina/Curso-de-excel/blob/main/Screen%20Shot%202022-03-31%20at%209.02.04%20PM.png) 

En este dataset se puede identificar los órdenes o pedidos que los usuarios hacen a Alibaba

# Clase 2 - Barra de menú y sus funcionalidades
Guardar el archivo en file/Save as/.xlsx
En la celda en la que estés parada se hacen los respectivos cambios de letra-tamaño
Si hundes la letra te selecciona la columna, si hundes el número te selecciona toda la fila. 

Para poder visualizar el signo $ lo que tienes que hacer es seleccionar columna/data/texto en columna/paso 3/(,) a (.)
Seleccionar la columna (sin título) click en mouse y bajas/ control+shift bajas al último dato
Para restar un valor se debe variable 1(letra#)-variable 2(letra#)
Copiar y pergar FÓRMULA (CLICK derecho copy paste)
Copiar y pegar el mismo resulta (barra de menú/paste/paste value)

# Clase 3 - Filtros y herramientas de revisión
Seleccionar todo/Insert/Table
Data/Filter/Flecha/permite elegir una fila y visualiszarla sola en la tabla 

*Click advance para elegir fechas*

# Clase 4 - Funcionalidades de un libro y sus hojas
Hojas (sheets) 
Son en la parte inferior y están compuestas por celdas
Cambiar el nombre/color/eliminar/mover la hoja: doble click o click derecho
Se puede seleccionar múltiples hojas con CTRL + click y eliminarla al mismo tiempo

# Clase 5 - Herramientas para trabajar con bases de datos
Si se van a hacer cambios en la hoja pero no quieres que se cambien algunos datos toca ir a view/freeze y elegir la mejor opción 
Si se busca inmovilizar una columna en específico solo es pararse en ella y darle click para que se mantenga a pesar de mover el doc
comando A para seleccionar todos los datos

Si añades los filtros y le pones color a las celdas, excel te va a permitir luego ordenar tú hoja por colores
![Resumen clase](https://github.com/otravalentina/Curso-de-excel/blob/main/Screen%20Shot%202022-04-22%20at%201.48.04%20PM.png)

# Clase 6 - Consulta información 
Buscar v: sirve para hojas que tienen miles de datos y permite buscar el valor de la orden específica, para poder copiar y pegarla en la hoja donde queremos tener la información
  =vlookup(valor buscado "# de la celda";matriz o tabla "seleccionar todos los datos que se buscan tener";columna "el valor del flete/shipping fee;coincidencia exacta "False")
  
Valor buscado: Lo que necesitas buscar.
Matriz de tabla: En donde lo buscaras.
Indicador de la columna: Cuando encuentres lo que buscas, que tomaras de esa tabla. Siempre identifica los encabezados de la tabla en la que estas buscando para poder contar la columna que necesitas.
Rango: Solo tienes dos opciones: Verdadero o Falso. El Verdadero es cuando ocupas algo similar a lo que buscas, y el Falso es cuando es exactamente lo que buscas.
  
Puedes pegar la fórmula (no el dato) sosteniendo el mouse y seleccionando todas las celdas que quieres llenar. O copiar la fórmula y con el mini cuadrado bajar hasta la celda que quieres llenar. 

*Aclaración* si escriben un 1 en excel y le ponen formato fecha veran que se convierte en “domingo, 1 de enero de 1900”.
Esto por que las fecha excel las entiende de forma numérica como la cantidad de días que han pasado desde el 01-01-1900.

# Clase 7 - Valores absolutos y relativos en fórmulas

Ctrl + espacio: selecciona la columna 
Shift (dereacha) + espacio: selecciona la fila

para añadir fila arriba ctrl + click y le das en "insert"

Fijar.- Representado por el símbolo $, nos ayuda a fijar ya sea una columna o fila.
Fijar Columna ($A) .- Esto hace que la formula tome información de diferentes filas sin alterar la información de una columna en especial.
Fijar Filas ($1) .- Al contrario Fijar una fila hace que la formula tome información de diferentes columnas sin alterar la información de una fija específica.

*Si se busca usar buscarv es necesario que los datos que se encuentres en una columna después sino sale N/A*
















