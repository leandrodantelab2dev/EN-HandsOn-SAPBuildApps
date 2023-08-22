## Ejercicio 05 - Creación de la página de detalles del producto

En este paso, personalizaremos el formulario de producto detallado.

Que está en el menú de páginas en la esquina superior izquierda.

Seleccione la página, __Product Detail__.

![MDK](images/img1.png)

Inicialmente configuremos los datos.
Haga clic en el interruptor del botón Seleccionar variables.

![MDK](images/img2.png)

En el menú lateral, seleccione __Data Variables__.

Agrega uno Data Variable, __Products__.

![MDK](images/img3.png)

Cambie el nombre de Data Variable.
```dv_products_item```

Selecciona el __Single data record__, Porque solo necesitamos un registro.

Y cuál será el filtro para seleccionar la ID, nos referiremos al parámetro de datos, que vendrá de la página de inicio.

clickea en __ID__.

![MDK](images/img4.png)

Seleccione __Formula__.

![MDK](images/img5.png)

Seleccione __Create Formula__.

![MDK](images/img6.png)

Y agregar como valor:

```NUMBER(params.idproduct)```

Y mantener la fórmula.

![MDK](images/img7.png)

Volveremos a __View__,Para editar el formulario. 
 Elimine el texto que no usaremos.

![MDK](images/img8.png)

Cambie el contenido del título al nombre de producto que vendrá de la variable de datos.

![MDK](images/img9.png)

Seleccione __Data and Variables__.

![MDK](images/img10.png)

Seleccione __Data variable__.

![MDK](images/img11.png)

Seleccione __dv_products_item__.

Y __Name__.

![MDK](images/img12.png)

Guardar el Bind del nombre del producto.

![MDK](images/img13.png)

Pon un título como encabezado para descripciones de productos.

Cambie la pestaña de estilo su tipografía, como H3.

![MDK](images/img14.png)

Renomeie para Rating.

![MDK](images/img15.png)

Similar ao Icon Button, procuraremos um novo elemento dentro da lojinha do SAP Build.

Neste caso precisamos de um Star Rating.

![MDK](images/img16.png)

En la tienda Búsqueda de: __rating__.

Y seleccionar __Star Rating__.

![MDK](images/img17.png)

Clickea en__Install__.

![MDK](images/img18.png)

Ahora disponible como elemento de página, agregue al canvas; Cambiar el valor máximo a 5; Y cambiar el valor de enlace.

![MDK](images/img19.png)

Seleccione __Data and Variables__.

![MDK](images/img20.png)

Seleccione __Data variables__.

![MDK](images/img21.png)

Seleccione la data variable configurado.

Y seleccione el __Rating__.

![MDK](images/img22.png)

Guarde la selección.

Para los otros campos, haga lo mismo hasta que tengamos la forma completa.

Siendo los valores:
- Product ID.
- Price.
- Release Date.

![MDK](images/img23.png)
![MDK](images/img24.png)
![MDK](images/img25.png)
![MDK](images/img26.png)
![MDK](images/img27.png)
![MDK](images/img28.png)
![MDK](images/img29.png)
![MDK](images/img30.png)
![MDK](images/img31.png)

Con el formulario de detalle del producto tenemos nuestra segunda funcionalidad completada.

## Proximo paso:
[Ejercicio 06 - Creación de la funcionalidad de búsqueda de código QR](/exercises/ex6/README.md)
