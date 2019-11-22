## Crear enlaces

En esta tarjeta aprenderá cómo hacer un enlace que lo lleve a otra página cuando se hace clic.

- Agregue el siguiente código a la sección del cuerpo de `index.html`:

```html
  <a href="">Haga clic aquí</a>
```

Las etiquetas `<a> </a>` convierten lo que haya entre ellas en un enlace.

- Intenta hacer clic en tu enlace para ver qué sucede. No hace nada, ¿verdad?

Esto se debe a que el atributo `href` está vacío en este momento. Debe contener la **URL** (dirección web) de la página a la que desea vincular.

- Vaya a Wikipedia y encuentre una página sobre algo en su sitio web. Voy a usar la página sobre Irlanda.

- Haga clic en la barra de direcciones y seleccione todo el texto en i5. Esa es la URL completa de la página en la que estás. presione el <kdb>Ctrl</kdb> (o <kdb>cmd</kdb>) y <kdb>C</kdb> teclas al mismo tiempo para copiarlo.
    
    ![URL en la barra de direcciones](images/AddressBarURL.png)

- En su abalorio, haga clic entre comillas después de `href =` y presione el <kdb>Ctrl</kdb> (o <kdb>cmd</kdb>) y <kdb>V</kdb> teclas al mismo tiempo para pegar la URL que acaba de copiar. Su código debería verse así ahora:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">Haga clic aquí</a>
```

¡Acabas de crear tu primer enlace! Haga clic para ver si funciona ahora.

![Etiqueta de enlace](images/egLinkTagWithURL.png)

## \--- collapse \---

## title: Enlaces a otros sitios web

Trinket tiene problemas con algunas direcciones web. Si lo desea, puede probar las URL de sitios web que no sean Wikipedia, pero es posible que no funcionen en su baratija. Sin embargo, si tuviera que descargar su proyecto y ver los archivos en un navegador web, vería que los enlaces funcionan.

\--- /collapse \---

- Intente poner una imagen entre las etiquetas `<a> </a>` lugar de las palabras `Haga clic aquí`, así:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">
      <img src="tito.png" alt="Tito the dog" width="100px" />
  </a>
```

- Haz clic en tu foto. ¿Ves que se convirtió en un enlace?

También puede poner un enlace en otros elementos de su página web, como en un párrafo o incluso en una lista. Aquí hay un ejemplo de una oración con un enlace:

```html
  <p>
    <a href="https://en.wikipedia.org/wiki/Ireland">Haga clic aquí</a> para leer la página de Wikipedia!
  </p>
```

\--- desafío \---

## Desafío: poner un enlace en una lista

- Vea si puede hacer una lista que contenga un enlace dentro de uno de los elementos de la lista.

\--- /challenge \---