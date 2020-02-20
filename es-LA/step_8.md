## Creating links

On this card you'll learn how to make a link that takes you to another page when it's clicked.

- Add the following code to the body section of `index.html`:

```html
  <a href="">Click here</a>
```

The `<a> </a>` tags turn whatever is in between them into a link.

- Try clicking your link to see what happens. It does nothing, right?

That's because the `href` attribute is empty at the moment. It needs to contain the **URL** (web address) of the page that you want to link to.

- Go to Wikipedia and find a page about something on your website. I'm going to use the page about Ireland.

- Click in the address bar and select all of the text in it. That's the complete URL of the page you're on. Press the <kdb>Ctrl</kdb> (or <kdb>cmd</kdb>) and <kdb>C</kdb> keys at the same time to copy it.
    
    ![URL in address bar](images/AddressBarURL.png)

- In your trinket, click in between the quotation marks after `href=` and press the <kdb>Ctrl</kdb> (or <kdb>cmd</kdb>) and <kdb>V</kdb> keys at the same time to paste in the URL you just copied. Your code should look something like this now:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">Click here</a>
```

You just created your first link! Click on it to see if it works now.

![Link tag](images/egLinkTagWithURL.png)

## \--- collapse \---

## title: Links to other websites

Trinket has trouble with some web addresses. You can try URLs of websites other than Wikipedia if you like, but they may not work in your trinket. However, if you were to download your project and view the files in a web browser, you would see the links working.

\--- /collapse \---

- Try putting a picture in between the `<a> </a>` tags instead of the words `Click here`, like this:

```html
  <a href="https://en.wikipedia.org/wiki/Ireland">
      <img src="tito.png" alt="Tito the dog" width="100px" />
  </a>
```

- Click on your picture. Do you see that it was turned into a link?

You can put a link into other elements of your webpage too, such as in a paragraph or even in a list. Here is an example of a sentence with a link in it:

```html
  <p>
    <a href="https://en.wikipedia.org/wiki/Ireland">Click here</a> to read the Wikipedia page!
  </p>
```

\--- challenge \---

## Challenge: put a link into a list

- See if you can make a list that contains a link inside one of the list items.

\--- /challenge \---