# Ejercicio 3 - Creación de la página de inicio

Ahora estamos en el tiempo mágico, personalizamos nuestra forma.

Comencemos por cambiar el título, a __Product List__

![MDK](images/img1.png)

No usaremos este campo de texto, haremos clic en él y haremos clic en el __X__ para remover.

![MDK](images/img2.png)

Ahora necesitamos un botón de icono para agregarlo a nuestros objetos disponibles.

Clickea en __Marketplace__ Para acceder a la tienda SAP Build.

![MDK](images/img3.png)

Búsqueda por __button__.

Seleccionar __Icon Button__.

![MDK](images/img4.png)

Con el botón de icono seleccionado, haga clic __Install__.

![MDK](images/img5.png)

Con el botón de icono disponible en nuestra cuadrícula de objetos, agregaremos al Canvas.

![MDK](images/img6.png)

Cambia tu contenido e icono
![MDK](images/img7.png)

Para el cambio de icono, seleccione __Icon__.

![MDK](images/img8.png)

Busque QR y seleccione el icono.

![MDK](images/img9.png)

Ahora agregemos la lista, que representará todos los productos.

En el menú del lado izquierdo, seleccione __Core__, Encuentra el objeto __Icon list Item__, y agregar al Canva.

![MDK](images/img10.png)

Intercambie el icono de la lista a uno que tenga sentido con el producto, en mi escenario usaré el icono de efectivo disponible en la biblioteca de iconos Fiori.

![MDK](images/img11.png)

Seleccionar __Icon__.

![MDK](images/img12.png)

Cambiar a la biblioteca Fiori Icons.

![MDK](images/img13.png)

Seleccione el cajero.

![MDK](images/img14.png)

Para cargar la lista, necesitamos vincular la lista a la Data Variables.

Clickea en __Repeat With__.

![MDK](images/img15.png)

Seleccionar __Data and Variables__.

![MDK](images/img16.png)

Seleccionar __Data variable__.

![MDK](images/img17.png)

Seleccionar __dv_products__.
Y guarda la selección.

![MDK](images/img18.png)

Ahora tenemos nuestra lista con los elementos repetidos cargados, cambiemos la etiqueta para relacionarnos con el elemento de carga.

En la etiqueta primaria, seleccione.

![MDK](images/img19.png)

Seleccionar __Data item in repeat__.

![MDK](images/img20.png)

Busque el elemento de nombre, que son los datos principales que se muestran en la lista.

Seleccionar __current__.

Seleccionar __Name__.

![MDK](images/img21.png)

También cambie el valor de vista previa establecida a: ```ProductName```
 
Y guarde los cambios.

![MDK](images/img22.png)

También cambiaremos la etiqueta secundaria al precio.

![MDK](images/img23.png)

Seleccionar __Data item in repeat__.

![MDK](images/img24.png)

Busque el elemento de precio, que son los datos secundarios que se muestran en la lista.

Seleccionar __current__.

Seleccionar __Price__.

![MDK](images/img25.png)

Clickea en __SAVE__.

![MDK](images/img26.png)

Finalmente, guarde su página de inicio, completamente construida.
![MDK](images/img27.png)

## Proximo paso:

[Ejercicio 04 - Navegación entre la página de inicio y la página de detalles del producto](/exercises/ex4/README.md)
