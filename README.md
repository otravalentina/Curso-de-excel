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

# Clase 14 - Cómo separar y juntar texto
Remover las fórmulas y dejar solo el resultadi: Selecciona las fórmulas que quieres cambiar con Cmd + C, luego Home > Paste > Values

Para separar 1 dato número como una fecha: +month(celda de la fecha) > inicio > formato fecha

Para separar 1 palabra: señalar la columna > datos > text to columns > next > space > finish

Para concatenar (unir) datos: =concatenate/Concatenar(dato 1; dato 2; dato 3)

Para conatenar (unir) datos con espacios: =concatenate(dato 1; " "; dato 2; " "; dato 3)

Separar el dato a la derecha: =right(dato a la derecha; # de caracteres que se quieren coger del dato)

Separar el dato a la izquierda: = left(dato a la izquierda; # de caracteres que se quieren coger del dato)

# Clase 15 - Fórmulas básicas
Estás operaciones se hace de manera absoluta

Sumar: =SUM/SUMAR(dato1;dato2 "o" seleccionar toda la fila) 

Promedio: =AVERAGE/PROMEDIO(dato1;dato2 "o" seleccionar toda la fila)

Contar: =COUNT/CONTAR(dato1;dato2 "o" seleccionar toda la fila)

Redondear: =ROUND/REDONDEAR(dato1;# de decimales)

En la misma celda sumar/redondear: =ROUND(SUMA(dato1;dato2);0)

# Clase 16 - Fórmulas con SUMAR.SI, PROMEDIO.SI y CONTAR.SI
Estás operaciones se hace de manera relativa

Seleccionar datos > datos > filtrar > dato buscado 

Sumar.Si/SUM.IF (sumar con condiciones): (rango que va a estar el criterio; "Apple"; rango de las unidades)

Promedio.Si/AVERAGEIF: (rango; "Criterio"; rango de las unidades)

Contar.Si/COUNTIF: (rango; "Criterio")

Función de número aleatorio en inglés es +RANDBETWEEN()

# Clase 17 - Nombrar rangos y hacer operaciones
Se pueden nombrar los rangos al seleccionarlos y cambiarles el nombre en la parte superior izquierda. 

Al realizar la fórmula:
=SUMAR.SI(Proveedores;"Apple";Cantidad) me arrojaba siempre como resultado = 0, 
 la solución fue simplemente eliminar todos los espacios de la hoja de excel.

Eliminar espacios: control + f y reemplazar todo por nada, automáticamente se reemplazan/en el buscador de la hoja de excel y darle en la lupa "búsqueda avanzada"

# Clase 18 - Promedio ponderado
Para calcular el promedio de calificaciones, cada trabajo/ventas tiene un procentaje o peso diferente. 

Promedio general (se le asigna el mismo peso a cada valor): =PROMEDIO(variable A;Variable E) 
  *Seleccionar todas las variables a sacar el promedio*
  
Promedio ponderado forma 1(cada peso tiene un valor diferente): VentasxPeso y luego si PROMEDIO (variable 1; Variable E)
  *Al final para hacer promedio de esto será la suma de los promedios ponderados*
Promedio ponderado forma 2 (simple): =SUMAPRODUCTO(H2:H8;I2:I8)
  

# Clase 19 - Funciones y fórmulas útiles para tu día a día (resumen hasta ahora)
BuscarV: Use BUSCARV cuando necesite buscar elementos en una tabla o en un rango por fila. Por ejemplo, busque un precio de una parte de Automotive por el número de pieza o busque un nombre de empleado basándose en su identificador de empleado.

BuscarH: Busca un valor en la fila superior de una tabla o una matriz de valores y devuelve un valor en la misma columna de una fila especificada en la tabla o matriz. Use BUSCARH cuando los valores de comparación se encuentren en una fila en la parte superior de una tabla de datos y desee encontrar información que se halle dentro de un número especificado de filas.

Use BUSCARV cuando los valores de comparación se encuentren en una columna a la izquierda de los datos que desea encontrar.

Suma: La función suma agrega valores. Puede sumar valores individuales, referencias o rangos de celda o una combinación de las tres.

Promedio: Devuelve el promedio (media aritmética) de los argumentos. Por ejemplo, si el intervalo A1:A20 contiene números, la fórmula =PROMEDIO(A1:A20) devuelve el promedio de dichos números.

Contar: La función CONTAR cuenta la cantidad de celdas que contienen números y cuenta los números dentro de la lista de argumentos. Use la función CONTAR para obtener la cantidad de entradas en un campo de número de un rango o matriz de números.

Sumar.si: Use la función sumar. Si para sumar los valores de un intervalo que cumplen los criterios especificados. Por ejemplo, supongamos que en una columna que contiene números, desea sumar solo los valores mayores que 5. Puede usar la fórmula siguiente: = sumar.si (B2: B25, “>5”)

Promedio.si: Devuelve el promedio (media aritmética) de todas las celdas de un rango que cumplen unos criterios determinados.

Contar.si: Use CONTAR.SI, una de las funciones estadísticas, para contar el número de celdas que cumplen un criterio; por ejemplo, para contar el número de veces que una ciudad determinada aparece en una lista de clientes.

Hoy: Devuelve el número de serie de la fecha actual. El número de serie es el código de fecha-hora que Excel usa para los cálculos de fecha y hora. Si el formato de celda es General antes de especificar la función, Excel cambia el formato de celda a Fecha. Si desea ver el número de serie, debe cambiar el formato de celda a General o Número.

Mes: Devuelve el mes de una fecha representada por un número de serie. El mes se expresa como número entero comprendido entre 1 (enero) y 12 (diciembre).

Espacios: Elimina los espacios del texto, excepto el espacio normal que se deja entre palabras. Use ESPACIOS en texto procedente de otras aplicaciones que pueda contener un espaciado irregular.

Concatenar: La función CONCAT combina el texto de varios rangos o cadenas, pero no proporciona argumentos delimitadores o de IgnoreEmpty. CONCAT reemplaza la función concatenar. Sin embargo, la función CONCATENAR seguirá estando disponible por motivos de compatibilidad con versiones anteriores de Excel.

Derecha: DERECHA devuelve el último carácter o caracteres de una cadena de texto, según el número de caracteres especificado. DERECHAB devuelve el último carácter o caracteres de una cadena de texto, según el número de bytes especificado.

Izquierda: IZQUIERDA devuelve el primer carácter o caracteres de una cadena de texto, según el número de caracteres que especifique el usuario. IZQUIERDAB devuelve el primer carácter o caracteres de una cadena de texto, en función del número de bytes especificados.

Redondear: La función REDONDEAR redondea un número a un número de decimales especificado.

Promedio ponderado: La función SUMAPRODUCTO devuelve la suma de los productos de los rangos o matrices correspondientes. La operación predeterminada es la multiplicación, pero también es posible sumar, restar y dividir.

# Clase 20 - Fórmulas condicionales
2 valores y se necesita hacer una a.) verificación (número mayor, menos o igual) entre el primero o el segundo b.) dependiendo del resultado se va a querer una acción dependiendo si es verdadero o falso. 

= si(condición;acción a;acción b)
= si(valor celda > valor celda;v;f)
Ejemplo con verdadero/falso: =+SI(I10>800;"Aplica bono";"No pasa nada") *siempre poner las comillas para que sean tomadas en cuenta*
Ejemplo con verdadero/falso/igual: =+SI(I10>800;"Aplica bono";SI(I10=800;"falta poco"; "No pasa nada"))

# Clase 21 - Formatos condicionales y el formato semáforo
Para poder aplicar un color a las celdas: escoger toda la columna > ir a inicio > escoger formato condicional > darle en más reglas > estilo clásico > solo aplicar en las celdas que contengan > valor de las celdas > igual a > Aplica bono
Para poder aplicar un color a las celdas (3 colores): escoger toda la columna > ir a inicio > escoger formato condicional > darle en más reglas > 3 colores (asegurarse que los tres colores sean distintos). 
  *Los colores en degrade según que tan alto o bajo está el precio según la condición elegida*
  
# Clase 22 - Tabla dinámica
Tabla dinámica: Seleccionar los datos que quieren ser incluidos en la tabla dinámica > insertar > Tabla > Tabla dinámica > hoja nueva

Una vez la tabla hecha, si tienes una tabla muy grande debes elegir que variables poner en las columnas y qué otras en las filas (arrastrarlos)

Para editar la tabla hacer control + click y así se podrá editar el diseño, color, letra de la tabla, etc. 

Para hacer operaciones con los datos de una tabla dinámica: Entrar a la tabla dinámica > Análisis de tabla dinámica > campo calculado > Nombre de la columna > Fórmula > "= venta/cantidad > sumar > aceptar

# Clase 23 - Gráficas
Gráficos: seleccionar tabla > insertar > gráfico de elección > diseño
![Resumen de la clase de excel](https://github.com/otravalentina/Curso-de-excel/blob/main/Screenshot_101-bedb8b9a-7134-4f31-b72b-86e8af05e605.jpg.png.jpeg)

# Clase 24 - Gráficas dinámicas y minigráficas

![Resumen de la clase de excel](https://github.com/otravalentina/Curso-de-excel/blob/main/Screenshot_102-0f32a875-ca85-4605-8647-842af82a972f.jpg.png.jpeg)

# Clase 25 - Protger la información
Proteger todo el documento: Control + A > Inicio > proteger > Número > Bloqueada > revisar > proteger hoja > contraseña (para poder modificar)
Desproteger solo una celda: pararse en la celda > número > protgeger > quitar lo de bloquear 
Impedir que se añada otra hoja al libro: proteger libro > contraseña > check en la estructura del libro 

# Clase 26 - Imprimir
Tip 1: Si sólo quieren imprimir una área que seleccionaron, no es necesario definir el área de impresión. Pueden hacerlo de manera rápida:
1 - Seleccionen el rango que desean imprimir.
2 - Ir a Archivo->Imprimir
3 - En la opción que por defecto está en “Imprimir hojas activas” Seleccionan "Impirmir Selección"
4- Click imprimir.

tip 2: Nunca se confien de la vista previa de impresión, impriman en un pdf primero antes de gastar papel y si les parece como se ve, pueden proceder a imprimir fisicamente.
tip 3: Imprimir filas o columnas intercaladas. Por ejemplo, quieren imprimir solo las columnas A, B, E y F.

1 - Ocultar las columnas o filas que no deseamos imprimir. 
2 - Seleccionar las columnas visibles, que son las deseadas. 
3 - Configurar el área de impresión como en la clase: Ir a menú Diseño de página -> Área de impresión -> Establecer área de impresión -> Vista preliminar
4 - Convertir a PDF o imprimir si es muy necesario.

# Clase 27 - Crea un menú a tú reporte
Seleccionar columnas/filas darle ctrl + click y darle en ocultar (hasta el final para que se genere un espacio en gris). 

Crear hipervínculo: insertar > ilustraciones > formas > (la de preferencia) > "escribir un nombre" > click + ctrl > hipervínculo > seleccionar criterios (si es una hoja creada o una hoja por crear...) 












