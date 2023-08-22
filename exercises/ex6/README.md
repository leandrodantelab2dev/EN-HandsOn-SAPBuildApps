# Ejercicio 6 - Creación de la funcionalidad de búsqueda de código QR

En este paso, agregaremos la funcionalidad de buscar un producto por código QR utilizando la cámara del dispositivo.

Para esto, utilizaremos un acelerador de SAP Build que nos axilará en este desafío.

En la esquina superior izquierda, haga clic en el menú de navegación.

Y seleccione la página de inicio.

![MDK](images/img1.png)

Seleccione el botón de escaneo de código QR, ya que es que agregaremos nuestra lógica.

Y haga clic en: __Add logic to ICON BUTTON 1__.

![MDK](images/img2.png)

Tenga en cuenta que en nuestro menú del lado izquierdo también tenemos nuestra tienda.

Procure por: __Scan QR__, y agregar al tablero.

![MDK](images/img3.png)

También agregar __Open Page__, Porque tan pronto como leemos la identificación del producto, necesitamos navegar a la página de detalles.

![MDK](images/img4.png)

Interconectar los Nodes para que tenga un flujo.

![MDK](images/img5.png)

Seleccione el Node del OpenPage y cambiemos la página de apertura.

En la esquina derecha, seleccione __Page__.

![MDK](images/img6.png)

Seleccione __Page ID__.

![MDK](images/img7.png)

Seleccione el detalle del producto y __Save__.
![MDK](images/img8.png)

Ahora seleccionaremos lo que contendrá en el __ID Product__.
Usaremos una variable de otro nodo, que será de Scan QR.

Seleccione __Output value of another node__.

![MDK](images/img10.png)

Seleccione __Scan QR/barcode__.

![MDK](images/img11.png)

También seleccione el objeto __Scan QR/barcode content__.

E guarde.

![MDK](images/img13.png)

¡Listo! Ahora tenemos nuestra funcionalidad de búsqueda QR lista. Guarde su aplicación y esté listo para probar.

![MDK](images/img14.png)

## Proximo paso:
[Ejercicio 07 - Ejecución y pruebas](/exercises/ex7/README.md)