# Ejercicio 04 - Navegación entre la página de inicio y la página de detalles del producto

En este paso, construiremos la navegación entre la página de inicio y los detalles, donde contendrá los datos del producto en detalle.

En la esquina superior izquierda, haga clic __Home Page__, Para acceder al resumen de todas las páginas.

![MDK](images/img1.png)

Agregue una nueva página, haga clic en __ADD NEW PAGE__.

![MDK](images/img2.png)

Nombre como Product Detal.
Clickea en __OK__.

![MDK](images/img3.png)

Con la nueva página creada, vaya a las variantes para configurar el PAGE PARAMETERS.

![MDK](images/img4.png)

En el menú del lado izquierdo, seleccione __PAGE PARAMETERS__.

Clique __ADD PARAMETERS__.

Configure el nombre del parámetro como:
```idproduct```

![MDK](images/img5.png)

Vuelva al editor gráfico haciendo clic en el Switch Button.

![MDK](images/img6.png)

Acceda al menú de navegación haciendo clic en la esquina superior izquierda, en la etiqueta azul.

Y navegue a la página de inicio, para agregar la lógica de navegación.

![MDK](images/img7.png)

Seleccione la lista de productos para agregar lógica.

Clickea en: __Add logic to ICON LIST ITEM 1__.

![MDK](images/img8.png)

En los elementos de la lógica, agregue:__Open page__.

Y conecte el evento a la navegación.

![MDK](images/img9.png)

Seleccione la página que se abrirá por:__Page__.

![MDK](images/img10.png)

Seleccione la página __Product Detail__ e __Save__.

![MDK](images/img11.png)

Habilitará un campo: __idproduct__.

Seleccione qué elemento se aplicará como valor.

![MDK](images/img12.png)

Seleccione __Formula__.

![MDK](images/img13.png)

Seleccione __Create formula__.

![MDK](images/img14.png)

Complete el campo:

STRING(repeated.current.ID)

Y guardar la fórmula.

![MDK](images/img15.png)

## Proximo paso:
[Ejercicio 05 - Creación de la página de detalles del producto](/exercises/ex5/README.md)