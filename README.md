# **Brief**

## Proyecto: **BoMarket**
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Misión:

#### Ofrecer una manera de que las personas puedan mostrar sus productos (para comenzar hardware/componentes de computadoras) a vender en internet a través de un catálogo personal.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Target:
#### Para las personas que están comenzando o tienen su negocio en Bolivia-La paz. En este lugar el mercado en su mayoría es informal y la mayoría de las personas no pueden acceder al costo de una página web.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Propuesta:
#### Es una página web que va a tener usuarios los cuales podrán publicar sus productos para vender, y contarán con su propio catalogo para compartir y de esta manera poder generar trafico en la pagina web.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## MVP:
#### Cada persona que entre podrá buscar los productos que hay en la página. Los Vendedores contaran con un link para poder compartir con sus clientes su catálogo de productos en venta. En cada publicación y en el catálogo tendrán un acceso directo WhatsApp del vendedor.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Proyectos similares:
#### El proyecto que domina el mercado informal es el Marketplace de Facebook, pero no ofrece un acceso directo a el teléfono de los vendedores ya que no todos están conectados al messager-facebook siempre, pero si al WhatsApp, tampoco ofrece una manera fácil de poder compartir todos los productos que vendes.
#### Existe MercadoLibre, pero no tiene injerencia alguna en el país, acá no existe mercadopago ni mercadoenvios. 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Marca:
#### La Marca del proyecto es BoMarket, por el momento no hay dominio y tampoco logo, ya que la elección del mismo también iría acompañada de una selección de colores y cambios de colores en la página web.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Web:
# https://bomarket.vercel.app
# Scrum
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Planing (28 de Junio):

#### Partimos a partir de la base del proyecto del modulo 10 y 9 
#### Organizando la planning con lo que falta realizar en el código.
#### Viendo cómo distribuir los datos en la base de datos.
#### Escribimos los user stories en trello. 
#### (Aun no sabíamos como trabajar con GitHub en grupo)

#### Definimos roles:
#### Front-End:
	Álvaro Bastía.
#### Back-End:
	Francisco Ibarrola.
#### Fullstack:
	Matías Toledo.
#### Tareas:
#### Front-End:
•	Tener un catálogo por cada usuario
•	 Estilar la home de la e-commerce.
•	Modificar los estilos del perfil del usuario.
•	Estilar las cards.
•	Actualizar los datos del perfil.
•	Poder subir los productos a publicar.

#### Back-End:
•	Hacer form para cargar los productos (Back y Front).
•	Actualizar los datos del perfil del usuario.
•	Realizar el endpoint para el catálogo.
Elegimos la fecha: Daily 1: 30/06 a las 19hs Arg.

## Primer Daily (30 de Junio):

#### Se habla del Back-End para cambiar el editar perfil, y hacerlo en el Front-End. (Matías)
#### Se discute cómo encarar problemática del Back-End y la base de datos, para poder relacionar el usuario con los productos. 
#### Hablamos de como hacer la interface para editar productos, comparar si el token del usuario que está en la página es el mismo que el del vendedor del catálogo y si no, no dejar editar productos.
#### Agregar un icono de perfil desde el header de pc. (Matías)
#### Agregar las sweetalert en el login (quitar las alertas normales). (Álvaro)
#### Agregar categoría y stock de un producto (Matías).
#### Tengo que agregar la sync entre algolia y airtable 
#### Compartimos como trabajar en equipo con GitHub. O como era según lo que entendimos.
#### Se creo en Airtable una tabla que dice vendedores, con sus respectivos datos
#### Agregue a mis compañeros a los repositorios de GitHub, permisos en Algolia, Airtable y Firebase 
#### Elegimos la fecha: Daily 2: 01/07 a las 20hs Arg.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Segundo Daily (1 de Julio):

#### Realizamos las tareas que habíamos denominado para cada uno.
#### Añadimos estilos nuevos a componentes viejos.
#### Cree una endpoint y funciones en el Back-End para mostrar el catálogo de un vendedor, decidimos eliminar la tabla Vendedores de Airtable y usar directamente el userId de firebase y relacionarlo al producto. Se creo una columna en products para relacionarlo al usuario.
#### Álvaro creo los hooks necesarios para los nuevos componentes añadidos en el front.
#### Matías agrego un middleware para el tema de CORS
#### Elegimos la fecha: Daily 3: 02/07 a las 19hs Arg.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Tercer Daily: (2 de Julio):

#### Reconfiguré un error que había creado en algolia al hacer el catálogo, estaba investigando si podia remplazar Algolia por Airtable ya que tenian los mismos datos.
#### El Front-End no sube productos, debe arreglarse.
#### Hablamos de hacer el loader un componente (mejorar la optimización del código).
#### Álvaro realizo los componentes de editar y publicar productos, y mejorar estilos del menú de la página, también cambiamos el título de la página.
#### Matías arreglo el endpoint para modificar el usuario
#### Para hacer:
•	Corregir errores del back
•	Corregir errores del front
•	Añadir nuevas funcionalidades
•	Hacer el hook del sync
#### Elegimos la fecha: Daily 4: 05/07 a las 15hs Arg.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Cuarto Daily (5 de Julio):
#### Hice el endpoint para modificar, el producto y subirlo.
#### Cambiar detalles del Font del catálogo le toca a Álvaro.
#### Matías va a realizar una paginación, ya que la que teníamos anteriormente no resulta útil.
#### Mati hizo la paginación y reacomodo el endpoint para subir y editar productos.
#### Yo voy a ver de dividir las funciones de subir y editar productos para terminar con esa parte.
#### Elegimos la fecha: Daily 5: 06/07 a las 17hs Arg.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Quinto Daily (6 de Julio):
#### Yo realice el back para los productos destacados conectando con airtable por que consumía muchas request el que teníamos antes conectado a algolia.
#### Matías agrego la paginación en el Front-End 
#### Álvaro hizo lo del input y terminaría con detalles del front.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Retro (7 de Julio):
#### A Matías le pareció interesante, solo que teníamos maneras distintas de trabajar. Y no le pareció la mejor manera que teníamos de manejarnos con Github.
#### Álvaro lo sintió fluido al trabajo en equipo, se sintió el hecho de que sea el código de otra persona, pero tampoco fue un obstáculo. Le parecio interesante abordar una problemática fuera del país, también destaco la organización que tuvimos con los dailies.
#### En lo personal, creo que se noto la ausencia de un Scrum Master para algunas tomas de decisiones como con que herramientas trabajar y a la hora de hacer la planning.
#### Ya que hicimos una planning con stories pero alrededor de esas stories salieron muchos inconvenientes, se fueron solucionando al pasar los dailies pero habría sido mejor prevenir algunas cosas. 
#### Se noto la ausencia de un diseñador o de algo pensado de antemano ya que la pagina no esta muy al nivel que debería estar esteticamente. 
#### Para mejorar por mi parte, fui muy desordenado con los endpoint y las funciones en el backend.
#### Y para destacar es que hubo una buena organización como equipo y el compromiso con el proyecto. Nadie se sintió abrumado ni estancado al hacer las cosas.
#### Actualmente el proyecto como MVP esta bien. Pero tiene mucho camino por recorrer.

