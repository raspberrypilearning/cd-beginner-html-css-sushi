## Creando enlaces

En esta tarjeta, aprenderá cómo hacer un enlace que lo lleve a otra página cuando se haga clic.

- Agregue el siguiente código a la sección del cuerpo de `index.html`:

```html
  <a href="">Haga clic aquí</a>
```

Las etiquetas `<a> </a>` convierten lo que está entre ellos en un enlace.

- Intente hacer clic en su enlace para ver qué sucede. No hace nada, ¿verdad?

Eso es porque el atributo `href` está vacío en este momento. Debe contener la **URL** (dirección web) de la página a la que desea vincularse.

- Vaya a Wikipedia y busque una página sobre algo en su sitio web. Voy a usar la página sobre Irlanda.

- Haga clic en la barra de direcciones y seleccione todo el texto en i5. Esa es la URL completa de la página en la que se encuentra. presione el <kdb>Ctrl</kdb> (o <kdb>cmd</kdb>) y <kdb>do</kdb> teclas al mismo tiempo para copiarlo.
    
    ![URL en la barra de direcciones](images/AddressBarURL.png)

- En su baratija, haga clic entre las comillas después de `href =` y presione <kdb>Ctrl</kdb> (o <kdb>cmd</kdb>) y <kdb>V</kdb> teclas al mismo tiempo para pegar en la URL que acaba de copiar. Tu código debería verse más o menos así ahora:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">Haga clic aquí</a>
```

¡Acabas de crear tu primer enlace! Haga clic en él para ver si funciona ahora.

![Etiqueta de enlace](images/egLinkTagWithURL.png)

## \--- colapso \---

## title: Enlaces a otros sitios web

Trinket tiene problemas con algunas direcciones web. Si lo desea, puede probar las URL de sitios web que no sean Wikipedia, pero es posible que no funcionen en su baratija. Sin embargo, si descargara su proyecto y visualizara los archivos en un navegador web, vería que los enlaces funcionan.

\--- /colapso \---

- Intenta poner una imagen entre las etiquetas `<a> </a>` lugar de las palabras `Haz clic aquí`, como esta:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">
      <img src="tito.png" alt="Tito the dog" width="100px" />
  </a>
```

- Haga clic en su imagen. ¿Ves que se convirtió en un enlace?

También puede poner un enlace en otros elementos de su página web, como en un párrafo o incluso en una lista. Aquí hay un ejemplo de una oración con un enlace:

```html
  <p>
    <a href="https://en.wikipedia.org/wiki/Ireland">Haga clic aquí</a> para leer la página de Wikipedia!
  </p>
```

\--- desafío \---

## Desafío: poner un enlace en una lista

- Vea si puede hacer una lista que contenga un enlace dentro de uno de los elementos de la lista.

\--- / desafío \---