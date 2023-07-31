Autor: Simon Valles
Titulo: Preentrega numero 3. 


Objetivo del trabajo practico entregado:

Este programa consiste en el diseño de una pagina web en la cual se pueden crear:

-Articulos a vender
-Cursos ofertados  
-Ofertas de instrumentos (Articulos con descuento especial)
-Partners (compañias con convenios comerciales)

El programa contiene en el apartado de VIEWS las funciones principales y sus correspondientes formularios.
Adicionalmente la funcion buscarComision.

------------------------------------------------------------------------------------------------------
                    ¿COMO EJECUTAMOS EL PROGRAMA?

Direccion url para accesar a la pagina de inicio http://127.0.0.1:8000/aplicacion/inicio/

Como funcionalidades tenemos las siguientes aplicaciones:

-Haciendo click en los botones en cabecera se puede acceder a ARTICULOS-CURSOS-OFERTAS-PARTNERS-ADMINISTRACION
-En cada secciòn se visualizan los ARTICULOS-CURSOS-OFERTAS-PARTNERS precargados.
-Para la carga de datos podemos usar tres metodos:

    1. Mediante entradas al Browser: /articulosForm   /cursosForm    /ofertasForm     partnersForm
    2. via DBbrowser. Cargando los datos em las tablas generadas para cada modelo.
    3. por ADMINISTRACION (usuario: admin - contraseña: admin)

--------------------------------------------------------------------------------------------------------

Para cumplir con la consigna en cuanto a la busqueda dentro de la base de datos se generó el template
buscarComision.html que responde a la ruta  http://127.0.0.1:8000/aplicacion/buscarComision/

Esto nos redirecciona a una pagina en la cual se coloca el numero de comision y te devuelve todos los datos 
del curso, asociado a la comision buscada.
