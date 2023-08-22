# Ejercicio 2 - Configuración del proveedor de datos

Ahora integremos con nuestro backend.

Navegue a la pestaña __Data__.

![MDK](images/img1.png)

En esta pestaña tenemos muchas opciones de integración.
Estar integrado con SAP S/4, también utilizando el Conectivity > Destination.

En nuestro escenario usaremos __OData Integration__.

![MDK](images/img2.png)

Estos son los metadatos de nuestro backend

https://services.odata.org/V3/OData/OData.svc/

![MDK](images/img3.png)

Cole o endpoint sem campo "Base API URL", y hacer clic __Verify URL__, para llevar las entidades actuales de los metadatos.

![MDK](images/img4.png)

Seleccione la entidad de productos.

Y guardar, hacer clic en __SAVE DATA RESOURCES__.

![MDK](images/img5.png)

Ahora tenemos la entidad __Products__ disponible.

Clickea en __Save__.

![MDK](images/img6.png)

Con el __Data__ Ya configurado, tenemos que agregar a nuestra página, volver a Canvas, haciendo clic en __UI Canvas__.

Para acceder a las variables, podemos hacer clic en el Switch Button y acceder a las variables en la página.

![MDK](images/img7.png)

En la pestaña Data Variables, haga clic en __ADD DATA VARIABLES__.

![MDK](images/img8.png)

Y seleccione la entidad de productos.

![MDK](images/img9.png)

Rebautizar
```
dv_products
```

Y guardar, hacer clic en __SAVE__.

![MDK](images/img10.png)

Vuelva al formato gráfico haciendo clic nuevamente en el Switch Button.

![MDK](images/img11.png)

## Proximo paso:

[Ejercicio 03 - Creación de la página de inicio](/exercises/ex3/README.md)

