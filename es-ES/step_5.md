## Añadiendo imágenes

¡Agreguemos una foto!

- Ve a la pestaña llamada `index.html`. Busca la etiqueta `</main>` y escribe lo siguiente **encima**: 

```html
    <img src="tito.png" alt="Tito the dog" width="100px" />
```

Así es como debería verse el resultado:

![Código de imagen e imagen de Tito](images/egImgCodeTito.png)

Ten en cuenta que esta etiqueta tiene elementos adicionales de información dentro de ella. Se llaman **atributos**.

- Encuentra el elemento de código que dice `ancho = "100px"` e intenta experimentar con diferentes números para ver si puedes descubrir qué hace este atributo. ¡No borres las letras `px`!

## \--- collapse \---

## title: How the `img` tag works

Notice that the `<img>` tag is different from the other tags you've used so far — there is no closing `</img>` tag. Instead, this tag is **self-closing**: it has `/>` at the end. This is because there is no 'start' and 'end' to an image element like there is for text on the page.

The tag contains **attributes** with extra information:

- El atributo `src` le dice al navegador qué archivo usar para la imagen. 
- El atributo `alt` es una breve descripción que el navegador mostrará si no puede mostrar la imagen. 'alt' es la abreviatura de 'alternativa'. Este texto también ayuda a las personas que usan un lector de pantalla a saber cuál es la imagen.
- El atributo `width` le dice al navegador como de grande debe hacer la imagen. `100px` significa cien **píxeles**, que son los pequeños puntos que forman lo que estás viendo en tu pantalla. Si no incluyes este atributo, la imagen se mostrará en su tamaño original.

\--- /collapse \---

Now that you know the code to put a picture on your website, you probably want to change the picture, right?

- ¡Lo primero que necesitarás es, por supuesto, una imagen! Puedes usar una que ya tienes en tu ordenador, como una fotografía que tomaste, o puedes obtenerla a través de Internet.

[[[generic-get-picture-from-web]]]

**Note:** not all images you will find on the internet are free for anyone to use. If you download a picture, you should make sure it is one that you are allowed to use. Find out more about this here:

[[[images-permissions-to-use]]]

Once you have a picture, you can **upload** the file to Trinket:

- En Trinket, haz clic en el icono **imagen** lado del signo **+**. 

![The image icon](images/tktImageIconArrow.png)

This is where you can see the pictures that you are able to use on your website. You should see the picture of Tito, the CoderDojo dog.

- Haga clic en el botón **Agregar imagen** y luego haga clic en **Cargar**.

- Haz clic en el botón **Haga clic para seleccionar los archivos**. Busca y haz doble clic en tu archivo de imagen en la ventana que se abre.

- Haz clic en **Listo**.

![Image upload area](images/tktUploadImages.png)

Your picture will be uploaded and should be ready to use.

- Ve al archivo `index.html` y encuentra la etiqueta `<img>`. Cambia el texto `tito.png` para que coincida exactamente con el nombre del archivo de imagen que hayas elegido. ¡Ten en cuenta que su nombre puede terminar en `.jpg` en lugar de `.png`!

The text you just changed is the attribute called `src`, which tells the browser which file to display.

**Note:** the value you type for an attribute must have quotation marks `""` around it!

\--- challenge \---

## Challenge: change the alt text of the picture

- Encuentra el atributo `alt` de tu elemento de imagen y cambia el texto por una breve descripción de tu fotografía. 

\--- /challenge \---