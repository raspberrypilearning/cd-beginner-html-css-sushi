## Agregando imágenes

¡Agreguemos una foto!

- Vaya a la pestaña llamada ` index.html ` . Busca la etiqueta ` </main>` y escribe lo siguiente ** arriba de ella **: 

```html
    <img src="tito.png" alt="Tito the dog" width="100px" />
```

Así es como debería verse el resultado:

![Código de imagen e imagen de Tito](images/egImgCodeTito.png)

Ten en cuenta que esta etiqueta tiene información adicional en su interior. Se llaman **atributos**.

- Encuentra el bit de código que dice `width="100px"` e intenta experimentar con diferentes números para ver si puedes averiguar lo que hace este atributo. ¡No borres las letras `px`!

## \--- collapse \---

## title: Cómo funciona la etiqueta `img`

Ten en cuenta que la etiqueta `<img>` es diferente de las otras etiquetas que has utilizado hasta ahora: no hay etiqueta `</img>`. En cambio, esta etiqueta **se cierra automáticamente **: tiene `/>` al final. Esto se debe a que no hay un "inicio" y un "final" para un elemento de imagen como lo hay para el texto en la página.

La etiqueta contiene **atributos** con información adicional:

- El atributo `src` le dice al navegador qué archivo usar para la imagen. 
- El atributo `alt` es una descripción corta que el navegador mostrará si no puede mostrar la imagen. 'alt' es la abreviación de 'alternativo'. Este texto también ayuda a las personas que usan un lector de pantalla para saber qué es la imagen.
- El atributo `width` le dice al navegador qué tan ancha hacer la imagen. `100px` significa cien **pixels**, que son los puntos diminutos que conforman lo que estás viendo en tu pantalla. Si no incluyes este atributo, la imagen se mostrará en su tamaño original.

\--- /collapse \---

Ahora que conoces el código para poner una imagen en tu página web, probablemente desees cambiar la imagen, ¿verdad?

- Lo primero que necesitarás es, por supuesto, ¡una foto! Puedes usar una que ya tengas en tu computadora, como una fotografía que hayas tomado, o puedes obtener una de Internet.

[[[generic-get-picture-from-web]]]

**Nota:** no todas las imágenes que encontrarás en Internet son gratuitas para que cualquiera las use. Si descargas una imagen, debes asegurarte de que sea una que puedas usar. Obten más información sobre esto aquí:

[[[images-permissions-to-use]]]

Una vez que tengas una foto, puedes **subir** el archivo a Trinket:

- En tu Trinket, haz clic en el icono de **image** junto al signo **+**. 

![El icono de la imagen](images/tktImageIconArrow.png)

Aquí es donde puedes ver las fotos que puedes usar en tu sitio web. Deberías ver la foto de Tito, el perro CoderDojo.

- Haz clic en el botón ** Agregar imagen ** y luego haz clic en ** Subir **.

- Haz clic en el botón **Clic para seleccionar archivos**. Encuentra y haz doble clic en el archivo de imagen en la ventana que se abre.

- Haz clic en ** Listo **.

![Área de carga de imagen](images/tktUploadImages.png)

Tu foto se cargará y estará lista para usar.

- Ve al archivo `index.html` y encuentra la etiqueta `<img>`. Cambia el texto `tito.png` para que coincida exactamente con el nombre del archivo de imagen que has elegido. Ten en cuenta que el nombre puede terminar en `.jpg ` en lugar de `.png `!

El texto que acabas de cambiar es el atributo llamado `src`, que dice al navegador qué archivo mostrar.

**Nota:** ¡El valor que escribas para un atributo debe estar entre comillas `""`!

\--- challenge \---

## Desafío: cambia el texto alternativo de la imagen

- Encuentra el atributo `alt` de tu elemento de imagen y cambia el texto a una breve descripción de tu imagen. 

\--- /challenge \---