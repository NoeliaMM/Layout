
#####LABORATORIO BÁSICO#####

#EJERCICIO 1: Crear una paleta de colores dinámica. 

  En archivo exercise1 se importan los mixins para crear la 3 paletas de colores.
  El mixin create_pallete incluye dos iteraciones para añadir un background u otro en funcion de la clase darken o ligthen.

  En cada iteración se llama a la function text-color para ajustar el color del texto según el background.

  
#EJERCICIO 2:  Crear dos temas distintos y mostrar los resultados en una página.

Para probar este ejercicio cambiar en main.css el use:
  @use "exercise2_theme1" o @use "exercise2_theme2";


#EJERCICIO 3:  Barra de navegación con FlexBox

Se emplean medias querys para 3 tipos de resolución de pantalla :
 Mayores de 992px: Pantallas escritorio y laptops
 Entre 992 y 768 px: Tablets
 Por debajo de 768px: Móviles


#EJERCICIO 4:  Card con CssGrid

El contenedor usa display:grid para alinear y centrar la tarjeta.

Con grid-template-rows se distribuye el contenido en 3 filas. La primera fila de la imagen mantiene siempre el mismo alto y ajusta la imagen independientemente de su tamaño.

La sección del contenido principal también usa grid para organizar título, descripción y fecha.