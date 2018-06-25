## Agregar imágenes

Vamos a agregar una imagen!

- Vaya a la pestaña llamada `index.html`. Busque la etiqueta `</main>` y escriba los siguientes **arriba**: 

```html
    <img src="tito.png" alt="Tito the dog" width="100px" />
```

Este es el aspecto que debería tener el resultado:

![Código de imagen e imagen de Tito](images/egImgCodeTito.png)

Tenga en cuenta que esta etiqueta contiene bits de información adicionales. Se llaman **atributos**.

- Encuentra el bit de código que dice `width = "100px"` y prueba con diferentes números para ver si puedes averiguar qué hace este atributo. ¡No elimine las letras `px`!

\--- colapso \---

* * *

## title: Cómo funciona la etiqueta `<img>`

Tenga en cuenta que la etiqueta `<img>` es diferente de las otras etiquetas que ha utilizado hasta ahora: no hay</code> etiqueta de cierre `</img>` . En su lugar, esta etiqueta es **de cierre automático**: tiene `/>` en el extremo. Esto se debe a que no hay "inicio" ni "final" en un elemento de imagen como el texto en la página.

La etiqueta contiene **atributos** con información adicional:

- El atributo `src` le dice al navegador qué archivo usar para la imagen. 
- El atributo `alt` es una breve descripción que mostrará el navegador si no puede mostrar la imagen. 'alt' es la abreviatura de 'alternativa'. Este texto también ayuda a las personas que usan un lector de pantalla a saber cuál es la imagen.
- El atributo `width` le dice al navegador qué ancho hacer la imagen. `100px` significa cien **píxeles**, que son los puntos pequeños que componen lo que está viendo en la pantalla. Si no incluye este atributo, la imagen se mostrará en su tamaño original.

\--- /colapso \---

Ahora que conoce el código para poner una imagen en su sitio web, es probable que desee cambiar la imagen, ¿verdad?

- Lo primero que necesitarás es, por supuesto, una imagen. Puede usar uno que ya tenga en su computadora, como una fotografía que tomó, o puede obtener uno de Internet.

[[[generic-get-picture-from-web]]]

**Nota:** no todas las imágenes que encontrará en Internet son gratuitas para que las use cualquiera. Si descargas una imagen, debes asegurarte de que sea una que puedas usar. Descubre más sobre esto aquí:

[[[images-permissions-to-use]]]

Una vez que tenga una imagen, puede **subir** el archivo a Trinket:

- En su baratija, haga clic en el ícono de **imagen** lado del signo **+**. 

![El ícono de imagen](images/tktImageIconArrow.png)

Aquí es donde puede ver las imágenes que puede usar en su sitio web. Deberías ver la foto de Tito, el perro CoderDojo.

- Haga clic en el botón **Agregar imagen** y luego haga clic en **Cargar**.

- Haga clic en el botón **Haga clic para seleccionar archivos**. Encuentre y haga doble clic en su archivo de imagen en la ventana que se abre.

- Haga clic en **Hecho**.

![Área de carga de imagen](images/tktUploadImages.png)

Su foto será cargada y debería estar lista para usar.

- Vaya al archivo `index.html` y busque la etiqueta `<img>`. Cambie el texto `tito.png` para que coincida exactamente con el nombre del archivo de imagen que ha elegido. Tenga en cuenta que su nombre podría terminar en `.jpg` lugar de `.png`!

El texto que acaba de cambiar es el atributo llamado `src`, que le dice al navegador qué archivo mostrar.

**Nota:** el valor que escriba para un atributo debe tener comillas `""` a su alrededor.

\--- desafío \---

## Desafío: cambiar el texto alternativo de la imagen

- Encuentre el atributo `alt` de su elemento de imagen y cambie el texto en él a una breve descripción de su imagen. 

\--- / desafío \---