## Creating links

On this card you'll learn how to make a link that takes you to another page when clicked.

- Add the following code to index.html:

    ```html
    <a href="">Click here</a>
    ```
 The `<a> </a>` tag turns something into a link. 
 
- Try clicking your link to see what happens. It does nothing, right? 
  That's because the `href` **attribute** is empty at the moment. It needs to contain the **URL** \(web address\) of the page that you're linking to.

- Go to Wikipedia and find a page about something on your website. I'm going to use the page about Ireland.

- Click in the address bar and select all of the text. That's the whole **URL** of the page you're on. Press the **Ctrl** \(or **cmd**\) and **C** keys together to **copy** it. 

    ![URL in address bar](images/AddressBarURL.png)

- In your Trinket, click in between the quotation marks after `href=` and press the **Ctrl** \(or **cmd**\) and **V** keys together to **paste** in the URL you just copied. Your code should look something like this now:

    ```html
    <a href="https://en.wikipedia.org/wiki/Ireland">Click here</a>
    ```

    You just created your first link! Click on it to see if it works now.

    ![Link tag](images/LinkTagWithURL.png)

--- collapse ---
---
title: Links to other websites
---
Trinket has trouble with some links. You can try URLs for other websites than Wikipedia if you like, but the link may not work in your Trinket. It will work when you download your project and try it out in a browser later however.

--- /collapse ---

- Try putting a picture in between the `<a> </a>` tags instead of the words "Click here", like this:

    ```html
    <a href="https://en.wikipedia.org/wiki/Ireland">
        <img src="tito.png" alt="Tito the dog" width="100px" />
    </a>
    ```

- Click on your picture. Do you see that it was turned into a link?

You can put a link into other elements of your web page too, such as in a paragraph or even in a list. Here is an example of a sentence with a link in it:

    ```html
      <p>
        <a href="https://en.wikipedia.org/wiki/Ireland">Click here</a> to read the Wikipedia page!
      </p>
    ```


- Let's make a list of links for each new page you've created for you website. In the index.html file and add the following code:

   ```html
   <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="attractions.html">Places to visit</a></li>
      <li><a href="music.html">Music</a></li>
      <li><a href="food.html">Things to eat</a></li>
   </ul>
   ```

- Change the value of the `href` **attribute** for each link \(rememeber, that's the text inside the quotation marks\) so that it exactly matches the name of each new file that you created.

- Change the text in between the `<a> </a>` tags to suitable descriptions of your pages.

Now you can navigate to your new pages! 

