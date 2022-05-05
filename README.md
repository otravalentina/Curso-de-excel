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

# Clase 6/7/8 - Consulta información 
Buscar v: sirve para hojas que tienen miles de datos y permite buscar el valor de la orden específica, para poder copiar y pegarla en la hoja donde queremos tener la información
  =vlookup(valor buscado "# de la celda";matriz o tabla "seleccionar todos los datos que se buscan tener";columna "el valor del flete/shipping fee;coincidencia exacta "False")
  
Valor buscado: Lo que necesitas buscar.
Matriz de tabla: En donde lo buscaras.
Indicador de la columna: Cuando encuentres lo que buscas, que tomaras de esa tabla. Siempre identifica los encabezados de la tabla en la que estas buscando para poder contar la columna que necesitas.
Rango: Solo tienes dos opciones: Verdadero o Falso. El Verdadero es cuando ocupas algo similar a lo que buscas, y el Falso es cuando es exactamente lo que buscas.
  
Puedes pegar la fórmula (no el dato) sosteniendo el mouse y seleccionando todas las celdas que quieres llenar. O copiar la fórmula y con el mini cuadrado bajar hasta la celda que quieres llenar. 

*Aclaración* si escriben un 1 en excel y le ponen formato fecha veran que se convierte en “domingo, 1 de enero de 1900”.
Esto por que las fecha excel las entiende de forma numérica como la cantidad de días que han pasado desde el 01-01-1900.

# Clase 9 - Valores absolutos y relativos en fórmulas

Ctrl + espacio: selecciona la columna 
Shift (dereacha) + espacio: selecciona la fila

para añadir fila arriba ctrl + click y le das en "insert"

Fijar.- Representado por el símbolo $, nos ayuda a fijar ya sea una columna o fila.
Fijar Columna ($A) .- Esto hace que la formula tome información de diferentes filas sin alterar la información de una columna en especial.
Fijar Filas ($1) .- Al contrario Fijar una fila hace que la formula tome información de diferentes columnas sin alterar la información de una fija específica.

*Si se busca usar buscarv es necesario que los datos que se encuentres en una columna después sino sale N/A*

# Clase 10 - Consultas horizontales en BuscarH y tipos de errores en las fórmulas

Pegar información de manera horizontal:
- copiar y pegar cuadro/información
- click derecho en otra celda
- special paste
- special paste
- transpose

 =Hlookup(valor buscado "# de la celda";matriz o tabla "seleccionar todos los datos que se buscan tener";fila "el valor del flete/shipping fee;coincidencia exacta "False")
 
 Errores comunes:
 1. N/A: Te dice que ese dato no existe en el archivo original (de donde sacas la información)
 2. Nombre?: Cuando hay un error en la fórmula (se te fue una letra o número)
 3. REF!: Cuando intentas hacer una resta/suma/división/multiplicación con una celda que no existe en la hoja
 4. DIV/=: Cuando se intenta dividir cualquier número por 0 
 5. VALOR!: Las celdas que se relacionan no corresponden a valores que se puedan hcer funciones matemáticas

# Clase 11 - Formatos de celdas y archivos
La brochita al lado izquierdo de excel
1 click sobre la celda que que quieres repetir su formato
2 clicks para que te deje pegar el formato en varias celdas

Dejar el rastreo de los datos si vas a estar actualizando las hojas en las que trabajaste. Si e cambio, los valores en tú hoja son fijos no hay necesidad de dejar el historial de tus operaciones. 

Para la segunda opción solo se debe copiar y pararse donde exactamente se necesita pegar todo y pegar especial (valores)

Códigos
Calcular cuántos días han pasado desde el despacho: +TODAY()- Día despachado 
Restar: L3-K3 (escribir celda o hacerle click)

Buscar y Reemplazar: Home/Find&Select -> Replace (por lo que sea que quieras poner)

# Clase 12 - Malas prácticas al organizar una base de datos 
Malas prácticas al organizar una base de datos.
Títulos innecesarios.- Una mala práctica es crear diferentes títulos para enlistar fechas en lugar de tener una sola fila de referencia.
Ejemplo: Títulos de celdas “18/Oct 19/Oct 20/Oct” en lugar de tener una celda de referencia como ser “Fecha de Orden” donde se almacenaría todas esas fechas. La segunda celda es muy útil para manejar base de datos, la primera no.

Formato de Celda.- Otro error común tener una celda en un formato diferente que no nos permita realizar una acción.
Ejemplo: Tener una celda en formato texto y que esto nos impida realizar operaciones en ella.

El enemigo invisible.- Otro error común se encuentra en los nombres dentro de una casilla, esta puede contener espacios que son invisibles a simple vista pero que nos causan problemas al tener una base de datos. Solución: Usa la formula =espacios(texto) en texto pones la casilla donde quieres quitar los espacios y listo. (En otras versiones de Excel =ESPACIOS esta con el nombre de =RECORTAR)

Ceros delante de números.- Al momento de crear base de datos Excel elimina los ceros que estén delante de números automáticamente. 
Solución.- Pon un apostrofe (’) delante del numero, esto no te permitirá hacer operaciones con ese dato, pero si realizar búsquedas para las base de datos.

la fórmula espacio la encuentran como TRIM

 # Clase 13 - Listas desplegables
 
En una nueva hoja de cálculo, escriba las entradas que quiera que se muestren en la lista desplegable. Le recomendamos que muestre los elementos de lista en una tabla de Excel. Si no lo hace, puede convertir rápidamente la lista en una tabla si selecciona cualquier celda del rango y presiona Ctrl+T.

Haga clic en la celda de la hoja de cálculo donde quiera crear la lista desplegable.

Vaya a la pestaña Datos de la cinta de opciones y, después, seleccione Validación de datos.

Nota: Si no puede hacer clic en Validación de datos, es posible que la hoja de cálculo esté protegida o compartida. Desbloquee áreas específicas del libro protegido o deje de compartir la hoja de cálculo y, después, vuelva a intentar realizar el paso 3.

En la pestaña Configuración, en el cuadro Permitir, haga clic en Lista. Haga clic en el cuadro Origen y, después, seleccione el rango de lista. Colocaremos el nuestro en una hoja denominada “Ciudades”, en el rango A2:A9. Como puede ver, no incluimos la fila de encabezado porque no queremos que sea una opción de selección: Active la casilla Celda con lista desplegable y Haga clic en la pestaña Mensaje de entrada.

lista desplegable con opciones: solo se debe seleccionar los opciones cambiarles el nombres A5 -> "Procesos" de esa forma cuando se haga la lista desplegable tendrá múltiples opciones. 














